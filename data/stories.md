## greeting
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest

## Good
* positive
  - utter_positive

## Bad
* negative
  - utter_negative

## Bad covid, go quick
* greeting
  - utter_greeting
  - utter_q1
* affirmative
  - utter_call911

## No covid, stay at home
* greeting
  - utter_greeting
  - utter_q1
* negative
  - utter_q2
* negative
  - utter_q3
* negative
  - utter_q4
* negative
  - utter_q5
* negative
  - utter_q6
* negative
  - utter_stayHome

## New Story

* greeting
    - utter_greeting
    - utter_introduction
    - utter_startTest
* takeTest
    - utter_symptom1
* /
    - utter_confused
