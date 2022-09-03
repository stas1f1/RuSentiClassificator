# SentiChallenge

A Russian Sentiment analysis BERT model, fine-tuned for SA task from 
[RuBert-cased-conversational](https://huggingface.co/DeepPavlov/rubert-base-cased-conversational) 
with Sequence classification head, trained on [GoEmotions](https://ai.googleblog.com/2021/10/goemotions-dataset-for-fine-grained.html)
dataset which was translated to russian with help of Yandex Cloud Translate API.

Model is able to recognise un-emotional speech and 27 categories of emotions

Examples:
---
Ужасный сервис. Висит все утро, почините хоть что-то! : 
 отвращение
 
Добрый день, спасибо за быструю помощь! : 
 благодарность
 
Что вы собираетесь сделать по этому поводу? : 
 любопытство
 
Мне ничего не понятно из вашего объяснения : 
 замешательство
 
Крайне жаль что так произошло : 
 угрызение совести
 
Честно говоря, я расстроен работой вашей службы поддержки : 
 разочарование
 
 : 
 нейтральность
 
УРА, ВСЕ ВОССТАНОВИЛОСЬ : 
 восхищение
 
Ну и сколько мне еще ждать вашего ответа, м? : 
 любопытство
 
Жаль потраченного времени. : 
 разочарование
 
Да ну вас всех к черту : 
 злость
 
О господи : 
 удивление
 
ВЫ ЧТО ИЗДЕВАЕТЕСЬ?! ВЕРНИТЕ МНЕ ДЕНЬГИ НЕМЕДЛЕННО! : 
 злость
