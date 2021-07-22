# Tasks

დავალება:

1.დაწერეთ ფუნქცია, რომელსაც გადაეცემა ტექსტი  და აბრუნებს პალინდრომია თუ არა. (პალინდრომი არის ტექსტი რომელიც ერთნაირად იკითხება ორივე მხრიდან).

Boolean isPalindrome(String text);

2.გვაქვს 1,5,10,20 და 50 თეთრიანი მონეტები. დაწერეთ ფუნქცია, რომელსაც გადაეცემა თანხა (თეთრებში) და აბრუნებს მონეტების მინიმალურ რაოდენობას, რომლითაც შეგვიძლია ეს თანხა
დავახურდაოთ.

Int minSplit(Int amount);

3.მოცემულია მასივი, რომელიც შედგება მთელი რიცხვებისგან. დაწერეთ ფუნქცია რომელსაც გადაეცემა ეს მასივი და აბრუნებს მინიმალურ მთელ რიცხვს, რომელიც 0-ზე მეტია და ამ მასივში არ შედის.

Int notContains(Int[] array);

4.მოცემულია String რომელიც შედგება „(„ და „)“ ელემენტებისგან. დაწერეთ ფუნქცია რომელიც აბრუნებს ფრჩხილები არის თუ არა მათემატიკურად სწორად დასმული.
Boolean isProperly(String sequence);

მაგ: (()()) სწორი მიმდევრობაა,  ())() არასწორია

5.გვაქვს n სართულიანი კიბე, ერთ მოქმედებაში შეგვიძლია ავიდეთ 1 ან 2 საფეხურით. დაწერეთ ფუნქცია რომელიც დაითვლის n სართულზე ასვლის ვარიანტების რაოდენობას.

Int countVariants(Int stearsCount);

6.დაწერეთ საკუთარი მონაცემთა სტრუქტურა, რომელიც საშუალებას მოგვცემს O(1) დროში წავშალოთ ელემენტი.

7.გვაქვს Teacher ცხრილი, რომელსაც აქვს შემდეგი მახასიათებლები: სახელი, გვარი, სქესი, საგანი. გვაქვს Pupil ცხრილი, რომელსაც აქვს შემდეგი მახასიათებლები: 
სახელი, გვარი, სქესი, კლასი. ააგეთ ნებისმიერ რელაციურ ბაზაში ისეთი დამოკიდებულება, რომელიც საშუალებას მოგვცემს, რომ მასწავლებელმა ასწავლოს რამოდენიმე 
მოსწავლეს და ამავდროულად მოსწავლეს ჰყავდეს რამდენიმე მასწავლებელი (როგორც რეალურ ცხოვრებაში).

8.მოცემულია საქართველოს ეროვნული ბანკის RSS feed-ის მისამართი: http://www.nbg.ge/rss.php , რომელიც არბუნებს მიმდინარე ვალუტის კურსებს. დაწერეთ ფუნქცია, რომელსაც გადაეცემა ორი ვალუტის იდენტიფიკატორი(USD, GEL, EUR…) და აბრუნებს ვალუტებს შორის გაცვლის კურსს.

Double exchangeRate(String from, String to);
