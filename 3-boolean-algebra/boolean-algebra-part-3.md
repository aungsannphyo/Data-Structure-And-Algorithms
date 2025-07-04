# Rules in Boolean Algebra 

####  Part 3

##  Inversion Law or Complement Law

> #### A and !A = 0
> #### A or !A = 1

| A | !A | A and !A | A or !A |
| - | -- | ------   | ------  |
| 0 | 1  | 0        | 1       |
| 1 | 0  | 0        | 1       |

ဥပမာ အနေနဲ့  Safety Switch တစ်ခုရှိတယ်ဆိုပါစို့

**A** ကို Main Power ဖွင့်ထားတယ်လို့ထားလိုက်
**!A** ကို Emergency shutdown active ဖစ်တယ်လို့မှတ်ထားလိုက်

တကယ်လို့ Main Power ကို On ထားပီး Emergency shutdown active ဖစ်နေတယ်ဆိုရင် system က အလုပ်မလုပ်ဘူး
တကယ်လို့ Main Power က On မထားဘူး Emergency shutdown active ဖစ်နေတယ်ဆိုရင် system ကအလုပ်လုပ်မယ် ဒါမှမဟုတ်
Main Power က On ထားမယ်  Emergency shutdown က active ဖစ်မနေဘူးဆို system က အလုပ်လုပ်မယ်

---

##  Commutative Law

> #### A and B = B and A
> #### A or B = B or A

အထူးအဆန်းတော့မဟုတ်ပါဘူး 2 * 3 = 3 * 2 နဲ့ညီသလို 2 + 3 = 3 + 2 နဲ့ညီသလိုပါပဲ။
ကျွန်တော်ပြောဖို့မေ့နေ And ကိုမြှောက်တဲ့ **\*** symbol လို့သုံးပီး Or ကို **\+** symbol နဲ့လဲသုံးကြပါတယ်။

| A | B | A and B | B and A |
| - | - | -----   | -----   |
| 0 | 0 | 0       | 0       |
| 0 | 1 | 0       | 0       |
| 1 | 0 | 0       | 0       |
| 1 | 1 | 1       | 1       |

| A | B | A or B | B or A |
| - | - | -----  | -----  |
| 0 | 0 | 0      | 0      |
| 0 | 1 | 1      | 1      |
| 1 | 0 | 1      | 1      |
| 1 | 1 | 1      | 1      |


## Associative Law

> #### (A and B) and C = A and (B and C)
> #### (A or B) or C = A or (B or C)

## Distributive Law

> #### A and (B or C) = A and B or A and C
> #### A or (B and C) = (A or B) and (A or C)

ဒါလဲအပေါ်ကလိုပါပဲ truth table တော့ဆွဲမပြတော့ပါဘူးနော်။

---

## And Law

> #### A and 0 = 0
> #### A and 1 = 1
> #### A and A = A
> #### A and !A = 0

And က မှန်မှအလုပ်လုပ်တာဆိုတော ့ A က 1 ဆို 1 ထွက်မှာဖစ်ပီး 0 ဆို 0 ပဲထွက်တာဖစ်ပါတယ်။
A and A လုပ်မှတော့ တစ်ခုက 0 ဆို ကျန်တာလဲ 0 အဖြေက 0 ၊ တစ်ခုက 1 ဆိုကျန်တာကလဲ 1 အဖြေက 1။
A and !A ဆိုရင်တော့ တစ်ခုက 0 ဆို ကျန်တာလဲ 1 အဖြေက 0 ၊ တစ်ခုက 1 ဆိုကျန်တာကလဲ 0 အဖြေက 0။

| A | A and 0 |
| - | -----   |
| 0 | 0       |
| 1 | 0       |


| A | A and 1 |
| - | -----   |
| 0 | 0       |
| 1 | 1       |

| A | A and A |
| - | -----   |
| 0 | 0       |
| 1 | 1       |

| A | !A | A and !A |
| - | -- | ------   |
| 0 | 1  | 0        |
| 1 | 0  | 0        |


---

## Or Law

> #### A or 0 = A
> #### A or 1 = 1
> #### A or A = A
> #### A or !A = 1

Or ကအနည်းဆုံး တစ်ခုမှန်တာနဲ့အလုပ်လုပ်တာမို့ A က 0 ဆို 0, A က 1 ဆို 1 ပဲထွက်ပါလိမ့်မယ်။
1 နဲ့ Or လုပ်မှတော့ A က ဘာဖစ်ဖစ်  1 ပဲထွက်မှာဖစ်တယ်။
A or A လုပ်မှတော့ တစ်ခုက 0 ဆို ကျန်တာလဲ 0 အဖြေက 0 ၊ တစ်ခုက 1 ဆိုကျန်တာကလဲ 1 အဖြေက 1။
A or !A ဆိုရင်တော့ တစ်ခုက 0 ဆို ကျန်တာလဲ 1 အဖြေက 1 ၊ တစ်ခုက 1 ဆိုကျန်တာကလဲ 0 အဖြေက 1။

---

## Operator Precedence

ကျွန်တော်တို့ Or တွေ And တွေ not တွေသုံးတာတော့ဟုတ်ပီ သတိထားမိသလား **()** ဒီ curly bracket ကို အဲ့တာတွေက အလကားထည့်ထားတာမဟုတ်ဘူး ဘာကြောင့်လဲဆိုတော့ ဘယ်အရာကို အရင်လုပ်မလဲဆိုတာသတ်မှတ်ပေးတာဖစ်တယ် ပြောရရင် priority ဘယ်ဟာကိုအရင်းပေးမလဲပေါ့ အဲ့တာကို Operator Precedence လို့ခေါ်ပါတယ်။

| Priority | Operators |
| -------- | --------- |
| 1        | ()        | 
| 2        | !         | 
| 3        | And       |
| 4        | Or        | 

အပေါ်က table မှာပြထားသလို 1-4 အစဥ်အလိုက် အလုပ်လုပ်ကြပါတယ်။