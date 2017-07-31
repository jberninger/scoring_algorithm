# scoring_algorithm
this code takes as input a csv file from Survey Monkey with responses from the Thomas-Kilman Conflict Instrument. 
Users answered 30 A/B questions and the TKCI scoring algorithm gives them a 5 dimensional score on how they deal with conflist.
The 5 modes scored are compete, accommodate, avoid, collaborate, compromise. 
Everyone gets their raw score and their percentile in each category. 
This code parses the responses, computes the raw scores and returns the percentiles, following the scoring algorithm provided in a booklet.
