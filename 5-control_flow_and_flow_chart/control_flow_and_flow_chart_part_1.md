# Control Flow And Flowchart 

### Part 1

Algorithm ဆိုတာ Step by Step procedure လို့အရှေ့မှာပြောခဲ့တာမှတ်မိမယ်ထင်ပါတယ်။ ဥပမာ အနေနဲ့ ကျွန်တော်တို့ သူငယ်ချင်းတစ်ခု ဘီယာဆိုင်သွားတယ် သွားတဲ့အချိန်မှာ Tiger သောက်ဖို့ရောက်တော့ဆိုင်က ဆီပျက်နေတယ် တခြား Heineken ပဲရတယ်ဆို ကျွန်တော်တို့ကကြိုက်ရင်သောက်မယ် မကြိုက်ရင် တခြား Tiger ရတဲ့ဆိုင်ပဲသွားမယ် အဲ့သလို လုပ်မှဖစ်မယ် မလုပ်ရင်မဖစ်ဘူး ဆိုတဲ့အခြေအနေကို conditional or selection statement လို့ခေါ်တယ်။

![Flowchart](https://github.com/aungsannphyo/Data-Structure-And-Algorithms/blob/main/image/flowchart1.png?raw=true)

အပေါ်က Flowchart မှာဆိုရင် ရရင်သောက်မယ် မရခဲ့လိုရင်လဲ အဆင်ပြေရင်သောက်မယ် မသောက်ချင်ရင် တခြားဆိုင်ဆက်ရှာမယ်ဆိုတာကို ဥပမာ အနေနဲ့ ဆွဲပြထားတာဖစ်ပါတယ်။ Conditional က ရှူ့ထောင်အနေနဲ့နှစ်ဖက်စလုံးကနေလဲကြည့်လို့ရပါတယ်။ဘာကိုပြောချင်တာလဲဆိုရင် ပိုမြင်သာအောင် Pseudo Code အနေနဲ့ ရေးပြရရင်

```csharp
IF Tiger == true THEN
    drink
ELSE IF drink == true THEN
    drink
ELSE 
    findOtherBar
```
ဒါကတော့ အဆင်ပြေတယ် ပြောရရင် True ဆိုတဲ့အခြေအနေဘက် ရှူ့ထောင်ဖစ်တယ်


```csharp
IF Tiger == false THEN 
    IF drink === false THEN
        findOtherBar
    ELSE
        drink
ELSE 
    drink
```
ဒါကတော့ အဆင်မပြေဘူး ပြောရရင် False ဆိုတဲ့အခြေအနေဘက် ရှု့ထောင်ဖစ်တယ်

ဒါဆိုနောက်တမျိုးဆက်သွားကြည့်ရအောင် ဒီအခါမှာ ဥပမာအနေနဲ့ ကျွန်တော်တို့ ဆယ်တန်းစာမေးပွဲမှာ အနည်ဆုံး 80 ရရင် ဂုဏ်ထူးပါမယ် 40 အောက်ဆို ကျတယ် 40 အနည်းဆုံးရတယ်ဆို စာမေးပွဲအောင်တယ်။ အဲ့တော့ အရင်ဆုံး Pseudo code အနေနဲ့စဥ်းစားလိုက်ရအောင်


```csharp
IF Myanmar >= 40 AND English >= 40 AND Math >= 40 THEN
    IF Myanmar >= 75 OR English >= 75 OR Math >= 80 THEN
        OUTPUT "You pass the exam with D"
    ELSE 
        OUTPUT "You pass the exam"
ELSE
    OUTPUT "You fail the exam"
```

Nested မရေးချင်ရင်နောက်တနည်းရေးလို့ရပါသေးတယ်။

```csharp
IF Myanmar >= 40 AND English >= 40 AND Math >= 40 THEN
    OUTPUT "You pass the exam"
ELSE IF Myanmar >= 75 OR English >= 75 OR Math >= 80 THEN
    OUTPUT "You pass the exam with D"
ELSE
    OUTPUT "You fail the exam"
```

![Flowchart](https://github.com/aungsannphyo/Data-Structure-And-Algorithms/blob/main/image/flowchart2.png?raw=true)


### Conditional Statement for Range

Range တွေကို အဓိကစစ်တဲ့အခါ ကျွန်တော်တို့က AND ကိုပဲသုံးသင့်တယ်ဗျ။ တကယ်လို့သာ OR နဲ့ရေးခဲ့ရင် 

```csharp
If n >= 1 or n<=100 then:
```

အဲ့မှာ၀င်လာတဲ့ n တန်ဖိုးက အကယ်၍ 200 သာဖစ်မယ် ဒါမှမဟုတ် 20000 သာဖစ်မယ် ဆို True တန်းထွက်ပါလိမ့်မယ် ဘာလို့လဲဆိုတော့ 200 or 2000 က 1 ထက်ကြီးနေတာကိုး။ ဖစ်သင့်တာက 1 နဲ့ 100 ကြားလို့စစ်ချင်တဲ့အတွက် AND နဲ့စစ်သင့်တာဖစ်တယ် ဘယ်လိုလဲဆိုရင် 

```csharp
If n >= 1 and n <= 10 then:
```

နောက်ထပ်ဥပမာမြင်သာအောင်ပြရရင် 

```csharp
If mark>=90 then:
Write “grade A”
Else If mark<90 and mark>=70 then:
Write “grade B”
Else If mark<70 and mark>=40 then:
Write “grade C”
Else:
Write “grade D”
```

```csharp
If mark>=90 then:
Write “grade A”
Else mark>=70 then:
Write “grade B”
Else If mark>=40 then:
```