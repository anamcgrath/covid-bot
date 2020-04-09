## greeting
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest

## Path1 - No Test

* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* no
  - utter_noTest

## Path2 - Yes test
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* yes
  - utter_symptom1
* yes
  - utter_call911
  - utter_call911_2

## Path3 - yes doctor
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* yes
  - utter_symptom1
* no
  - utter_symptom_2
* yes
  - utter_consultDoctor

## Path4 - selfIsolate14
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* yes
  - utter_symptom1
* no
  - utter_symptom_2
* no
  - utter_symptom_3
* yes 
  - utter_stayHome
  - utter_stayHome_2
  - utter_travel
* yes 
  - utter_selfIsolate14
  - utter_selfIsolate14_2
  - utter_selfIsolate_3

## Path5 - selfIsolate10
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* yes
  - utter_symptom1
* no
  - utter_symptom_2
* no
  - utter_symptom_3
* yes 
  - utter_stayHome
  - utter_stayHome_2
  - utter_travel
* no
  - utter_provideCare
* yes
  - utter_selfIsolate10
  - utter_selfIsolate10_2
  - utter_selfIsolate10_3
  - utter_selfIsolate10_4

## Path6 - closeContact - selfIsolate10
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* yes
  - utter_symptom1
* no
  - utter_symptom_2
* no
  - utter_symptom_3
* yes 
  - utter_stayHome
  - utter_stayHome_2
  - utter_travel
* no
  - utter_provideCare
* no 
  - utter_closeContact
* yes
  - utter_selfIsolate10
  - utter_selfIsolate10_2
  - utter_selfIsolate10_3
  - utter_selfIsolate10_4

## Path7 - No Covid 
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* yes
  - utter_symptom1
* no
  - utter_symptom_2
* no
  - utter_symptom_3
* no
  - utter_travel
* no
  - utter_provideCare
* no
  - utter_closeContact
* no 
  - utter_noCovid
  - utter_noCovid_2
  - utter_noCovid_3

## Path8 - No - closeContact - selfIsolate10
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest
* yes
  - utter_symptom1
* no
  - utter_symptom_2
* no
  - utter_symptom_3
* yes 
  - utter_stayHome
  - utter_stayHome_2
  - utter_travel
* no
  - utter_provideCare
* no 
  - utter_closeContact
* no
  - utter_selfIsolate10
  - utter_selfIsolate10_2
  - utter_selfIsolate10_3
  - utter_selfIsolate10_4
