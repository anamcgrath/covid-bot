## greeting
* greeting
  - utter_greeting
  - utter_introduction
  - utter_startTest

## Path1 - No Test
* no_test
  - utter_noTest

## Path2 - Yes test
* start_test
  - utter_symptom1
* yes
  - utter_call911
  - utter_call911_2

## Path3 - yes doctor
* start_test
  - utter_symptom1
* no
  - utter_symptom_2
* yes
  - utter_consultDoctor

## Path4 - selfIsolate14
* start_test
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
* start_test
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
* start_test
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
* start_test
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
* start_test
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

## get started
* get_started
  - utter_greeting
  - utter_introduction
  - utter_startTest

## start over 
* greeting
  - utter_greeting
  - utter_introduction
  - utter_ startTest
  - action_session_start
