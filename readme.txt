
https://developer.amazon.com/edw/home.html#/

Intent Schema 

{
  "intents": [
    {
      "intent": "YesIntent"
    },
    {
      "slots": [
        {
          "name": "first",
          "type": "AMAZON.US_FIRST_NAME"
        }
      ],
      "intent": "AnswerIntent"
    }
  ]
}

Custom Slot Types (Optional)
Type 	Values 	
AMAZON.US_FIRST_NAME 	wenzhen

Sample Utterances
YesIntent yes
YesIntent sure
AnswerIntent {first}
AnswerIntent it's {first}
