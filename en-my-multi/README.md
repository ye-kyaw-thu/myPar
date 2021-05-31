# English-Myanmar Parallel Corpus with Multiple Translations for Myanmar Side

We developed two English-to-Myanmar parallel corpora for measuring the performance differences between Myanmar and English languages with the use of several possible Myanmar translations for the specific primary educational domain.  

Free for non commercial use! & Enjoy for NLP research purpose!!!  

## Files

English-Myanmar-one-to-one.ver0.9.txt (one-to-one translation)  
English-Myanmar-one-to-many.ver0.9.txt (one-to-many translation)    

As shown in the following, 8,394 sentences for one-to-one file and 48,494 sentences for one-to-many file.  

```
$ wc English-Myanmar-one-to-{one,many}.ver0.9.txt
   8394  111523  918304 English-Myanmar-one-to-one.ver0.9.txt
  48494  656589 5276766 English-Myanmar-one-to-many.ver0.9.txt
```

## Format

The format is: "English | Burmese"  

```
$ shuf ./English-Myanmar-one-to-one.ver0.9.txt | head -n 10
Is this hard ? | ဒါ ခက် ပါ သလား ။
It’s tall . | အဲ့ဒါ ရှည် ပါ တယ် ။
In the afternoon , I eat egg . | နေ့လည်ခင်း မှာ ကျွန်ုပ် က ဥ စား ပါ တယ် ။
chocolate | ချောကလက်
Is it a shirt ? | အဲဒါ က ရှပ်အင်္ကျီ တစ် ထည် ဖြစ် ပါ သလား ။
This is a ship and this is a shop . | ဒါ က သင်္ဘော တစ် စင်း ဖြစ် ပြီး ဒါ က ဆိုင် တစ် ဆိုင် ဖြစ် ပါ တယ် ။
It is a dog . | အဲ့ဒါ က ခွေး တစ် ကောင် ဖြစ် ပါ တယ် ။
It is a glass . | အဲဒါ က ဖန်ခွက် တစ် ခွက် ဖြစ် ပါ တယ် ။
I am a girl . | ငါ က မိန်းခလေး တစ် ယောက် ဖြစ် ပါ တယ် ။
This is my eye . | ဒါ ကျမ မျက်လုံး ဖြစ် ပါ တယ် ။
```

```
$ sed -n 15943,15968p ./English-Myanmar-one-to-many.ver0.9.txt 
It’s a cat . | ထိုအရာ သည် ကြောင် တစ် ကောင် ဖြစ် ပါ သည် ။
It’s a cat . | ထိုအရာ သည် ကြောင် တစ် ကောင် ဖြစ် သည် ။
It’s a cat . | ဒါ က ကြောင် တစ် ကောင် ပါ ။
It’s a cat . | ဒါ က ကြောင် တစ် ကောင် ဖြစ် တယ် ။
It’s a cat . | ဒါ က ကြောင် တစ် ကောင် ဖြစ် ပါ တယ် ။
It’s a cat . | ဒါ က ကြောင် တစ် ကောင် လေ ။
It’s a cat . | ဒါ ကြောင် တစ် ကောင် ပါ ။
It’s a cat . | ဒါ ကြောင် တစ် ကောင် ဖြစ် တယ် ။
It’s a cat . | ဒါ ကြောင် တစ် ကောင် ဖြစ် ပါ တယ် ။
It’s a cat . | ဒါ ကြောင် တစ် ကောင် လေ ။
It’s a cat . | အဲဒါ က ကြောင် တစ် ကောင် ပါ ။
It’s a cat . | အဲဒါ က ကြောင် တစ် ကောင် ဖြစ် တယ် ။
It’s a cat . | အဲဒါ က ကြောင် တစ် ကောင် ဖြစ် ပါ တယ် ။
It’s a cat . | အဲဒါ က ကြောင် တစ် ကောင် လေ ။
It’s a cat . | အဲဒါ ကြောင် တစ် ကောင် ပါ ။
It’s a cat . | အဲဒါ ကြောင် တစ် ကောင် ဖြစ် တယ် ။
It’s a cat . | အဲဒါ ကြောင် တစ် ကောင် ဖြစ် ပါ တယ် ။
It’s a cat . | အဲဒါ ကြောင် တစ် ကောင် လေ ။
It’s a cat . | အဲ့ဒါ က ကြောင် တစ် ကောင် ပါ ။
It’s a cat . | အဲ့ဒါ က ကြောင် တစ် ကောင် ဖြစ် တယ် ။
It’s a cat . | အဲ့ဒါ က ကြောင် တစ် ကောင် ဖြစ် ပါ တယ် ။
It’s a cat . | အဲ့ဒါ က ကြောင် တစ် ကောင် လေ ။
It’s a cat . | အဲ့ဒါ ကြောင် တစ် ကောင် ပါ ။
It’s a cat . | အဲ့ဒါ ကြောင် တစ် ကောင် ဖြစ် တယ် ။
It’s a cat . | အဲ့ဒါ ကြောင် တစ် ကောင် ဖြစ် ပါ တယ် ။
It’s a cat . | အဲ့ဒါ ကြောင် တစ် ကောင် လေ ။
```

## Publication

Please cite following paper:  

Honey Htun, Ye Kyaw Thu, Nyein Nyein Oo and Thepchai Supnithi, "English-Myanmar (Burmese) Phrase-Based SMT with One-to-One and One-to-Multiple Translations Corpora", In Proceedings of the 18th International Conference on Computer Applications (ICCA 2020), Feb 27-28, 2020, Yangon, Myanmar, pp. 189-198. [Paper](https://ieeexplore.ieee.org/document/9022851)  

