https://rebeccawilkins.github.io/pl1/services/mydirections.md

# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json
?origin=place_id:ChIJ75TkT_8EzkwRbp_CYE-1awI
&destination=place_id:ChIJFXSeVtQFzkwROBOzBsy314I
&waypoints=place_id:ChIJY99Yb1sEzkwR3D3lmp_Bw6E
|place_id:ChIJ7T7MY1MEzkwReMFJh479D7Q
|place_id:ChIJL-0QIPEEzkwRxPx5idTJaKo
|place_id:ChIJO8pWMg4PzkwRP0X3kCcAp3c
|place_id:ChIJr7uduUwFzkwRRtMmJLoP8tI
&mode=bicycling
&avoid=highways
&units=metric
&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ75TkT_8EzkwRbp_CYE-1awI",
         "types" : [ "establishment", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJY99Yb1sEzkwR3D3lmp_Bw6E",
         "types" : [ "establishment", "museum", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ7T7MY1MEzkwReMFJh479D7Q",
         "types" : [ "establishment", "museum", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJL-0QIPEEzkwRxPx5idTJaKo",
         "types" : [ "establishment", "museum", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJO8pWMg4PzkwRP0X3kCcAp3c",
         "types" : [
            "clothing_store",
            "establishment",
            "museum",
            "point_of_interest",
            "store",
            "tourist_attraction"
         ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJr7uduUwFzkwRRtMmJLoP8tI",
         "types" : [ "establishment", "museum", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJFXSeVtQFzkwROBOzBsy314I",
         "types" : [ "establishment", "museum", "point_of_interest", "tourist_attraction" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 45.4600827,
               "lng" : -75.6139972
            },
            "southwest" : {
               "lat" : 45.3877384,
               "lng" : -75.724969
            }
         },
         "copyrights" : "Map data ©2022 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "1.5 km",
                  "value" : 1486
               },
               "duration" : {
                  "text" : "6 mins",
                  "value" : 349
               },
               "end_address" : "1 Vimy Pl, Ottawa, ON K1A 0M8, Canada",
               "end_location" : {
                  "lat" : 45.4165723,
                  "lng" : -75.7168995
               },
               "start_address" : "Wellington St, Ottawa, ON K1A 0A9, Canada",
               "start_location" : {
                  "lat" : 45.4218391,
                  "lng" : -75.70445650000001
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "10 m",
                        "value" : 10
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.4217643,
                        "lng" : -75.70438879999999
                     },
                     "html_instructions" : "Head \u003cb\u003esoutheast\u003c/b\u003e toward \u003cb\u003eVittoria St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "omftGz_amMNM"
                     },
                     "start_location" : {
                        "lat" : 45.4218391,
                        "lng" : -75.70445650000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 113
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 45.4212219,
                        "lng" : -75.7056113
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVittoria St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_mftGl_amMTt@tA|D"
                     },
                     "start_location" : {
                        "lat" : 45.4217643,
                        "lng" : -75.70438879999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "93 m",
                        "value" : 93
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 45.42052200000001,
                        "lng" : -75.70494769999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eWellington St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 34\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "siftG`gamMjCcC"
                     },
                     "start_location" : {
                        "lat" : 45.4212219,
                        "lng" : -75.7056113
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 485
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 102
                     },
                     "end_location" : {
                        "lat" : 45.4189568,
                        "lng" : -75.7104875
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWellington St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 34\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "geftG|bamMrAfEBHPj@`A~CPj@Tr@L`@jAnD@FDPBJLb@D^BV@V@J?D?TAZAPAHAPAJCVGh@Gh@"
                     },
                     "start_location" : {
                        "lat" : 45.42052200000001,
                        "lng" : -75.70494769999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 488
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 117
                     },
                     "end_location" : {
                        "lat" : 45.4163335,
                        "lng" : -75.71479269999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e to stay on \u003cb\u003eWellington St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 34\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "o{etGpebmMKlBAP?JAH?J@T@RDPH^FVJ\\Pj@L\\N\\PZLT^^\\ZPLFFFBPHv@`@bA`@PHPJBBB@LLPPVXR\\NXFNZv@BHFH"
                     },
                     "start_location" : {
                        "lat" : 45.4189568,
                        "lng" : -75.7104875
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 168
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 45.41545139999999,
                        "lng" : -75.7165327
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eSir John A. Macdonald Parkway W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "aketGl`cmMVl@t@hBb@fAt@jBFN"
                     },
                     "start_location" : {
                        "lat" : 45.4163335,
                        "lng" : -75.71479269999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 129
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 45.4165723,
                        "lng" : -75.7168995
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eVimy Pl\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qeetGhkcmMA?g@Ty@NSDa@HeAT?A"
                     },
                     "start_location" : {
                        "lat" : 45.41545139999999,
                        "lng" : -75.7165327
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "4.4 km",
                  "value" : 4446
               },
               "duration" : {
                  "text" : "19 mins",
                  "value" : 1143
               },
               "end_address" : "240 McLeod St, Ottawa, ON K2P 2R1, Canada",
               "end_location" : {
                  "lat" : 45.4130556,
                  "lng" : -75.6888941
               },
               "start_address" : "1 Vimy Pl, Ottawa, ON K1A 0M8, Canada",
               "start_location" : {
                  "lat" : 45.4165723,
                  "lng" : -75.7168995
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "72 m",
                        "value" : 72
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 45.4159452,
                        "lng" : -75.7167211
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e",
                     "polyline" : {
                        "points" : "qletGrmcmM?@dAU`@IRE"
                     },
                     "start_location" : {
                        "lat" : 45.4165723,
                        "lng" : -75.7168995
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 319
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 45.414091,
                        "lng" : -75.7197346
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "uhetGnlcmM@?TLNTR\\R^NZJRPl@F\\F\\?@HTFPFLB@FBDBJNb@x@P^JRRTX`AHNPRPPNN"
                     },
                     "start_location" : {
                        "lat" : 45.4159452,
                        "lng" : -75.7167211
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 471
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 76
                     },
                     "end_location" : {
                        "lat" : 45.4117732,
                        "lng" : -75.72422349999999
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "polyline" : {
                        "points" : "a}dtGh_dmM^F|@NLBHDHBDD@?HJFHFJLNFJFFHHHFJHFFFHDFv@zANXDLFNBLHTHb@H`@BTJz@BPD`@@JJdAFj@Hj@Hn@RtA@JFX"
                     },
                     "start_location" : {
                        "lat" : 45.414091,
                        "lng" : -75.7197346
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1284
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 253
                     },
                     "end_location" : {
                        "lat" : 45.40399530000001,
                        "lng" : -75.71388159999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTrillium Pathway\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "qndtGj{dmMB?@?@@B@@@BB@B@B@FDXDXFVFR?@DHBFBBB@B@B?B?@?DCNGHG\\Q@?NKJK@AHGNMHKHKHOFMZs@\\w@HQHSJ]DOPg@Rq@La@DKDKLSHKBE~@kBl@cAl@eAZk@Xm@Re@Pg@N_@N[^u@N[HQFMDGFELKLKHGHMJM?AFIFGDELIFGDEHIJMBE\\i@T]LUPYXa@HOLSR_@Tk@Rg@Rg@Xk@l@cAp@mAr@gAz@oAf@u@b@s@b@y@R_@Re@Xc@"
                     },
                     "start_location" : {
                        "lat" : 45.4117732,
                        "lng" : -75.72422349999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2197
                     },
                     "duration" : {
                        "text" : "10 mins",
                        "value" : 609
                     },
                     "end_location" : {
                        "lat" : 45.4138337,
                        "lng" : -75.6895832
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eGladstone Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_~btGvzbmMMe@]iACQQw@Kc@EQEUCQ_@kBMi@Oo@WsAmAiGYcBQ{@K_@GQKQKOW_@MYGKIMKSKUWk@ISSa@GOEMGUGSaAeEm@oBCIk@gB_@mA[aASu@GOUe@Q[KQCIKUWu@{@qCUu@K_@y@gC_BeFa@sAOa@GQwB}GsC_JOi@I[kAwDWs@Qg@e@qAUw@IWGWYu@Ok@Wy@m@qBUs@YaAI[uAkEY}@Us@Om@"
                     },
                     "start_location" : {
                        "lat" : 45.40399530000001,
                        "lng" : -75.71388159999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 103
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 138
                     },
                     "end_location" : {
                        "lat" : 45.4130556,
                        "lng" : -75.6888941
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMetcalfe St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 89\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eWalk your bicycle\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m{dtGzb~lMtBeBd@_@AC"
                     },
                     "start_location" : {
                        "lat" : 45.4138337,
                        "lng" : -75.6895832
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "3.9 km",
                  "value" : 3891
               },
               "duration" : {
                  "text" : "16 mins",
                  "value" : 934
               },
               "end_address" : "100 Rue Laurier, Gatineau, QC K1A 0M8, Canada",
               "end_location" : {
                  "lat" : 45.42966999999999,
                  "lng" : -75.7099449
               },
               "start_address" : "240 McLeod St, Ottawa, ON K2P 2R1, Canada",
               "start_location" : {
                  "lat" : 45.4130556,
                  "lng" : -75.6888941
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "50 m",
                        "value" : 50
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 45.4128426,
                        "lng" : -75.6894621
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e toward \u003cb\u003eMcLeod St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "svdtGp~}lM@Bf@bB?D@B"
                     },
                     "start_location" : {
                        "lat" : 45.4130556,
                        "lng" : -75.6888941
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "23 m",
                        "value" : 23
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 45.4130104,
                        "lng" : -75.6896216
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eMcLeod St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "gudtGbb~lMABAB]V"
                     },
                     "start_location" : {
                        "lat" : 45.4128426,
                        "lng" : -75.6894621
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 128
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 45.4124268,
                        "lng" : -75.691031
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eMcLeod St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ivdtGbc~lM~@vCr@`C"
                     },
                     "start_location" : {
                        "lat" : 45.4130104,
                        "lng" : -75.6896216
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 905
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 245
                     },
                     "end_location" : {
                        "lat" : 45.4193702,
                        "lng" : -75.69706529999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eR. O'Connor St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 87\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "urdtG|k~lMcBtASNiA~@iBzAMLsBdBu@l@MLYV]V_Av@IDwAlAi@d@o@h@uAhACDu@l@q@j@QPEDOHiBzAwBhBKDk@b@OLMJc@b@"
                     },
                     "start_location" : {
                        "lat" : 45.4124268,
                        "lng" : -75.691031
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 181
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 86
                     },
                     "end_location" : {
                        "lat" : 45.4185489,
                        "lng" : -75.69906040000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eLaurier Ave W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 48\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "a~etGtq_mMHXFTLd@L^ZfAFH@FFN@DVx@l@lB"
                     },
                     "start_location" : {
                        "lat" : 45.4193702,
                        "lng" : -75.69706529999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 424
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 157
                     },
                     "end_location" : {
                        "lat" : 45.4217996,
                        "lng" : -75.70189289999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eBank St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 31\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}xetGb~_mMy@p@aAv@e@\\uBbBkAbAML]XWXEFGDGFGDWTg@`@KJWRy@n@e@^"
                     },
                     "start_location" : {
                        "lat" : 45.4185489,
                        "lng" : -75.69906040000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 763
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 181
                     },
                     "end_location" : {
                        "lat" : 45.4189568,
                        "lng" : -75.7104875
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eWellington St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 34\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gmftGxo`mM~@tCfAhDl@dBn@rB?@A@?@@@?B?@BHTp@rAfEBHPj@`A~CPj@Tr@L`@jAnD@FDPBJLb@D^BV@V@J?D?TAZAPAHAPAJCVGh@Gh@"
                     },
                     "start_location" : {
                        "lat" : 45.4217996,
                        "lng" : -75.70189289999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 696
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 115
                     },
                     "end_location" : {
                        "lat" : 45.4243843,
                        "lng" : -75.7140598
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePortage Bridge\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Quebec\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "o{etGpebmMOlAMd@EJKXKTW`@OJGFoAbAIFQNSPYTMJOLGFGFc@Z]V]PCBSL_@PUJUHKDODq@Rq@VSFYJk@P_A^GBWHMBa@Ja@JKBQBQBG@M@WBK?K@C?S?EAWCKA"
                     },
                     "start_location" : {
                        "lat" : 45.4189568,
                        "lng" : -75.7104875
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 706
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 113
                     },
                     "end_location" : {
                        "lat" : 45.4296745,
                        "lng" : -75.710143
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRue Laurier E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "k}ftGz{bmMGGGEGIIIACGKEICQEYCSGSGWGSQc@Ui@Uk@OWMUIUCEMSOWUYSWSU[YkBoAc@WQKUKa@QYIGCKB_@Ki@K_@Gu@KmAOeAK]C_@EmBS"
                     },
                     "start_location" : {
                        "lat" : 45.4243843,
                        "lng" : -75.7140598
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.42966999999999,
                        "lng" : -75.7099449
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e at \u003cb\u003eRue Papineau\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m~gtGjcbmM?g@"
                     },
                     "start_location" : {
                        "lat" : 45.4296745,
                        "lng" : -75.710143
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "9.4 km",
                  "value" : 9351
               },
               "duration" : {
                  "text" : "35 mins",
                  "value" : 2104
               },
               "end_address" : "Scientique, 1867 St. Laurent Blvd, Ottawa, ON K1G 5A3, Canada",
               "end_location" : {
                  "lat" : 45.4036414,
                  "lng" : -75.620245
               },
               "start_address" : "100 Rue Laurier, Gatineau, QC K1A 0M8, Canada",
               "start_location" : {
                  "lat" : 45.42966999999999,
                  "lng" : -75.7099449
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "83 m",
                        "value" : 83
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 45.4299926,
                        "lng" : -75.7090413
                     },
                     "html_instructions" : "Head \u003cb\u003eeast\u003c/b\u003e",
                     "polyline" : {
                        "points" : "m~gtGbbbmMAQ?QAOE[G[K[EICEMQII"
                     },
                     "start_location" : {
                        "lat" : 45.42966999999999,
                        "lng" : -75.7099449
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "46 m",
                        "value" : 46
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 6
                     },
                     "end_location" : {
                        "lat" : 45.4297254,
                        "lng" : -75.70861499999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "m`htGn|amMFOJOBCDGFEBEBC@CBU"
                     },
                     "start_location" : {
                        "lat" : 45.4299926,
                        "lng" : -75.7090413
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 104
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 45.4300253,
                        "lng" : -75.70779829999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "y~gtGxyamMACCIAQAU?OBQFQBW@MCMGKGCKAI?IBOH"
                     },
                     "start_location" : {
                        "lat" : 45.4297254,
                        "lng" : -75.70861499999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 236
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 40
                     },
                     "end_location" : {
                        "lat" : 45.431737,
                        "lng" : -75.7086458
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "u`htGvtamM@FAH?JELELGFEFEDE@C@G@K@I?MBG@G@C@MDOFIFIDKHE@E@C@E@C@EDEDCDGJCDIPEJEDEDEBM@G?EAE?ECEECECEGKCGIIIE"
                     },
                     "start_location" : {
                        "lat" : 45.4300253,
                        "lng" : -75.70779829999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 45.4316897,
                        "lng" : -75.7085161
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePont Alexandra\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kkhtG`zamMFW@A"
                     },
                     "start_location" : {
                        "lat" : 45.431737,
                        "lng" : -75.7086458
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 646
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 124
                     },
                     "end_location" : {
                        "lat" : 45.4290854,
                        "lng" : -75.70120969999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans Canada Trail\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Ontario\u003c/div\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "akhtGfyamMNIHYDQBKBGFSDQ?ABI@ABMDMDSPq@FUFYLc@@APw@@ENg@@CLg@@EPm@Ja@BILe@@GLe@@GNi@Pk@Ni@@ELi@@CNg@Lk@Po@Pm@Pm@Po@Nk@?APk@Nm@Ng@@CNi@L}@BGDa@?E@G?C?C?C?A?CEG"
                     },
                     "start_location" : {
                        "lat" : 45.4316897,
                        "lng" : -75.7085161
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 338
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 99
                     },
                     "end_location" : {
                        "lat" : 45.42857069999999,
                        "lng" : -75.69698579999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAlexandra Bridge\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "yzgtGpk`mM@O@w@?OAS@Y@SDc@DUDUJg@DMDWBMDU@OBWBg@@e@Am@@U@M?k@@UBc@Ds@NgBBe@"
                     },
                     "start_location" : {
                        "lat" : 45.4290854,
                        "lng" : -75.70120969999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 615
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 159
                     },
                     "end_location" : {
                        "lat" : 45.4242228,
                        "lng" : -75.6924252
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMackenzie Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 93\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qwgtGdq_mMPMb@]|@u@\\Y@APOf@c@fB{AdByALG\\_@DELMl@g@d@c@p@k@d@a@NMJWJiABWDQBMFM@EHQRY^[l@c@JIJGXW"
                     },
                     "start_location" : {
                        "lat" : 45.42857069999999,
                        "lng" : -75.69698579999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 366
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 61
                     },
                     "end_location" : {
                        "lat" : 45.4225552,
                        "lng" : -75.6884384
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eColonel By Dr\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eParts of this road are closed Sundays\u003c/div\u003e",
                     "polyline" : {
                        "points" : "k|ftGtt~lMDGLOHKFIJUHQL_@FQDQH[DOH]@I@GAMDMRy@Rs@Po@@GJ[L]FOp@mBHYTu@BG@EBIVeA"
                     },
                     "start_location" : {
                        "lat" : 45.4242228,
                        "lng" : -75.6924252
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "9 m",
                        "value" : 9
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 45
                     },
                     "end_location" : {
                        "lat" : 45.4226286,
                        "lng" : -75.68838629999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "_rftGv{}lMMI"
                     },
                     "start_location" : {
                        "lat" : 45.4225552,
                        "lng" : -75.6884384
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "55 m",
                        "value" : 55
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 45.4228732,
                        "lng" : -75.6878067
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "mrftGl{}lMAE?E?G?IAE?EAEAGAECEEIIMMQCE"
                     },
                     "start_location" : {
                        "lat" : 45.4226286,
                        "lng" : -75.68838629999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 462
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 65
                     },
                     "end_location" : {
                        "lat" : 45.42049249999999,
                        "lng" : -75.6830648
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}sftGxw}lMVk@J_@BI?CBQDSFQBGDIJILIHI@ABCBGDQR_ALk@F]FWDMBKBEDEFCFCBCDEDKTm@\\{@d@eAJWvCeH"
                     },
                     "start_location" : {
                        "lat" : 45.4228732,
                        "lng" : -75.6878067
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 153
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 64
                     },
                     "end_location" : {
                        "lat" : 45.4211843,
                        "lng" : -75.6826193
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aeftGbz|lMQSWYAAOQIKEECCAAAACCAAAA?CAA?A?C?C?A@C?C@E?C?C?C?CACAAAACAAAA?C?A@A@A??@A@?@ABAB?B?B@@?B?@@@@@BD@B@B@F?B@BAB?BABA@A@A@A?A@A?CACAEEEE"
                     },
                     "start_location" : {
                        "lat" : 45.42049249999999,
                        "lng" : -75.6830648
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "67 m",
                        "value" : 67
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 45.4207815,
                        "lng" : -75.68242549999999
                     },
                     "html_instructions" : "Sharp \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-sharp-left",
                     "polyline" : {
                        "points" : "kiftGjw|lMFTFFDDD@D@@?@ABCDGFO@E@C@ABG@EFOBE"
                     },
                     "start_location" : {
                        "lat" : 45.4211843,
                        "lng" : -75.6826193
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "10 m",
                        "value" : 10
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.42080929999999,
                        "lng" : -75.68232239999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "{fftGdv|lM@E?A?A?AA?ACAA?AA??A"
                     },
                     "start_location" : {
                        "lat" : 45.4207815,
                        "lng" : -75.68242549999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1136
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 179
                     },
                     "end_location" : {
                        "lat" : 45.4160333,
                        "lng" : -75.6696517
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "agftGnu|lM?A?A?AFKJW@CBC`AqAn@w@@EFQJUr@cB`@cATq@VaAFWLe@Ny@NgADWJ{@LmABMBSDSBO@OHg@l@kDl@wCb@qB@GBQHo@BWJo@FW?EJ_@BGDKLa@Ni@Rs@Ne@Nk@b@yAJc@Rw@v@yCH[b@yA^iADIBEDIJW@GPa@JWDGDG"
                     },
                     "start_location" : {
                        "lat" : 45.42080929999999,
                        "lng" : -75.68232239999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 699
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 139
                     },
                     "end_location" : {
                        "lat" : 45.4126433,
                        "lng" : -75.66394310000001
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "eietGhfzlMLOPQHGLINIp@[BAzAq@JEB?@?@A@ABAHEBA@AFCVMBA\\OPINI`@Q`@QNI\\MBABCHCBAJG@AJG^U@?LMNKJKFGBE@C@EHENMJIJOLUJYHSHa@@OBQB[?Y?QAe@Am@Cm@A_@CKAGCMCGAE?C?C?GFa@?G?C?E?GACMg@CIAI?K?MC_A@u@"
                     },
                     "start_location" : {
                        "lat" : 45.4160333,
                        "lng" : -75.6696517
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "89 m",
                        "value" : 89
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 16
                     },
                     "end_location" : {
                        "lat" : 45.4118471,
                        "lng" : -75.6639156
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_tdtGrbylMd@Cf@AbABJA"
                     },
                     "start_location" : {
                        "lat" : 45.4126433,
                        "lng" : -75.66394310000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 469
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 110
                     },
                     "end_location" : {
                        "lat" : 45.4120173,
                        "lng" : -75.6581836
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aodtGnbylM?G@E?CBIDG@C?C@AAOSeGGaBAM@G@M?MAOAGAIEIMKGECECEGUISCOAKAO?S?QBQPiA?I?MAMAGAMAMAG?G@IDcAFuADu@De@BQ@U"
                     },
                     "start_location" : {
                        "lat" : 45.4118471,
                        "lng" : -75.6639156
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 248
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 141
                     },
                     "end_location" : {
                        "lat" : 45.4116863,
                        "lng" : -75.65507119999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eIndustrial Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 30\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "cpdtGr~wlMGU^kFH{ADaAHiA@YLiB"
                     },
                     "start_location" : {
                        "lat" : 45.4120173,
                        "lng" : -75.6581836
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "25 m",
                        "value" : 25
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 45.4114705,
                        "lng" : -75.65514039999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "andtGdkwlMj@L"
                     },
                     "start_location" : {
                        "lat" : 45.4116863,
                        "lng" : -75.65507119999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 253
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 57
                     },
                     "end_location" : {
                        "lat" : 45.4101954,
                        "lng" : -75.6525542
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uldtGrkwlM@AT{@DMHQFOT_@d@q@Zm@^_ARs@L]LSV]HMBI@G@K?WAMAA"
                     },
                     "start_location" : {
                        "lat" : 45.4114705,
                        "lng" : -75.65514039999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "15 m",
                        "value" : 15
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 45.4100938,
                        "lng" : -75.6524216
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eNeighbourhood Way\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wddtGl{vlMTY"
                     },
                     "start_location" : {
                        "lat" : 45.4101954,
                        "lng" : -75.6525542
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1340
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 235
                     },
                     "end_location" : {
                        "lat" : 45.4084228,
                        "lng" : -75.6359042
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCoronation Ave.\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "addtGrzvlMMUEKEKMWIYIWG[EYEUC]Ec@C[?GCc@EmACcA?KC_AAyA?w@Aq@@_A?qA@y@?S@_@@oAFkBBq@@ONiD?GBe@De@@QB_@LwAViCLsAPmA@Ot@mFJo@`BgKJm@b@oCd@cDf@{CPoANaA"
                     },
                     "start_location" : {
                        "lat" : 45.4100938,
                        "lng" : -75.6524216
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1242
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 247
                     },
                     "end_location" : {
                        "lat" : 45.4008772,
                        "lng" : -75.62588719999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRussell Rd\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "syctGjsslM^?@?LANCLEJEPGp@c@vA_ApBoAhAs@j@_@jAu@XSTQ@APQdC_Ch@g@~@}@LMp@k@f@g@BCtAmANMJMHMJMHOFODMFQDOBMDOF_@D_@XsBd@eDT_Bx@iGHm@BWTkBL{@@M@KBKDGBEDGHCHCh@ETADAL@PA"
                     },
                     "start_location" : {
                        "lat" : 45.4084228,
                        "lng" : -75.6359042
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 155
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 68
                     },
                     "end_location" : {
                        "lat" : 45.40138959999999,
                        "lng" : -75.62409769999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSmyth Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 72\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ojbtGxtqlMA}@A[?EAC?EAQCUEQACG[Qq@Ma@KWQ]KW"
                     },
                     "start_location" : {
                        "lat" : 45.4008772,
                        "lng" : -75.62588719999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 301
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 81
                     },
                     "end_location" : {
                        "lat" : 45.402384,
                        "lng" : -75.62056
                     },
                     "html_instructions" : "Continue onto \u003cb\u003eLancaster Rd\u003c/b\u003e",
                     "polyline" : {
                        "points" : "umbtGriqlM_@_AESKa@Qe@Kg@Ia@_@sBUkAY_BQ_AIe@AK?MAK?M?OBS"
                     },
                     "start_location" : {
                        "lat" : 45.40138959999999,
                        "lng" : -75.62409769999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 124
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 43
                     },
                     "end_location" : {
                        "lat" : 45.4034159,
                        "lng" : -75.6208091
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{sbtGnsplMUWECA?GCK@KBMDSHa@Pm@XSHKD"
                     },
                     "start_location" : {
                        "lat" : 45.402384,
                        "lng" : -75.62056
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "54 m",
                        "value" : 54
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 45.4036414,
                        "lng" : -75.620245
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kzbtG`uplMIi@AEAICMGYAEACAACAEAA?"
                     },
                     "start_location" : {
                        "lat" : 45.4034159,
                        "lng" : -75.6208091
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "8.5 km",
                  "value" : 8472
               },
               "duration" : {
                  "text" : "29 mins",
                  "value" : 1766
               },
               "end_address" : "11 Aviation Pkwy, Ottawa, ON K1K 2X5, Canada",
               "end_location" : {
                  "lat" : 45.4581478,
                  "lng" : -75.6440037
               },
               "start_address" : "Scientique, 1867 St. Laurent Blvd, Ottawa, ON K1G 5A3, Canada",
               "start_location" : {
                  "lat" : 45.4036414,
                  "lng" : -75.620245
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "14 m",
                        "value" : 14
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.4037594,
                        "lng" : -75.6202902
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e",
                     "polyline" : {
                        "points" : "w{btGnqplMA@E?OF"
                     },
                     "start_location" : {
                        "lat" : 45.4036414,
                        "lng" : -75.620245
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "42 m",
                        "value" : 42
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 9
                     },
                     "end_location" : {
                        "lat" : 45.4036122,
                        "lng" : -75.6207884
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o|btGxqplMPbAFXBD"
                     },
                     "start_location" : {
                        "lat" : 45.4037594,
                        "lng" : -75.6202902
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 162
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 27
                     },
                     "end_location" : {
                        "lat" : 45.4032017,
                        "lng" : -75.6227281
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "q{btG|tplMA@ADAF@RD^FVDJBLd@jCLdB@JBJBB"
                     },
                     "start_location" : {
                        "lat" : 45.4036122,
                        "lng" : -75.6207884
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "11 m",
                        "value" : 11
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.4032618,
                        "lng" : -75.6228472
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eGladwin Crescent\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_ybtG`aqlMKV"
                     },
                     "start_location" : {
                        "lat" : 45.4032017,
                        "lng" : -75.6227281
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "65 m",
                        "value" : 65
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 45.4030371,
                        "lng" : -75.6236162
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eGladwin Crescent\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kybtGxaqlMj@xC"
                     },
                     "start_location" : {
                        "lat" : 45.4032618,
                        "lng" : -75.6228472
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "45 m",
                        "value" : 45
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 45.4034129,
                        "lng" : -75.62382769999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eGladwin Crescent\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_xbtGrfqlMiAh@"
                     },
                     "start_location" : {
                        "lat" : 45.4030371,
                        "lng" : -75.6236162
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 122
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 25
                     },
                     "end_location" : {
                        "lat" : 45.4031708,
                        "lng" : -75.62532200000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eSt. Laurent Blvd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 26 W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "izbtG|gqlMEt@AZDXF`@RfATrA"
                     },
                     "start_location" : {
                        "lat" : 45.4034129,
                        "lng" : -75.62382769999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 353
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 82
                     },
                     "end_location" : {
                        "lat" : 45.4060888,
                        "lng" : -75.62707690000001
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSt. Laurent Blvd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 26 W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yxbtGfqqlMaAd@cAb@UFA@g@VUJQLq@^u@f@}Az@EBg@VgAh@]N"
                     },
                     "start_location" : {
                        "lat" : 45.4031708,
                        "lng" : -75.62532200000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1274
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 220
                     },
                     "end_location" : {
                        "lat" : 45.4124615,
                        "lng" : -75.6139972
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eInnes Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 30\u003c/b\u003e (signs for \u003cb\u003eON-417\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "akctGf|qlMIGE?I?c@DOBE@E?CAC?MECAMMMc@m@sB]cAg@wA]aAUm@[u@AA]u@_@w@]s@KQGOSa@GK{@mBO_@Oc@Oe@Us@Sm@CMg@}Aq@_Co@wB_@oA_@kAY_AMa@GMCIwAyE_A{Cg@aBMc@AGQk@i@}AaA{Cq@wB"
                     },
                     "start_location" : {
                        "lat" : 45.4060888,
                        "lng" : -75.62707690000001
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 919
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 218
                     },
                     "end_location" : {
                        "lat" : 45.4201993,
                        "lng" : -75.617935
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eStar Top Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{rdtGnjolMSHiAb@OFSNiAh@WJi@X{BbAmAh@_@PgChAu@\\m@X}FjCaDxAeCfAoAh@]Pk@RKBOBK@I@IAI?IAGAGCGC"
                     },
                     "start_location" : {
                        "lat" : 45.4124615,
                        "lng" : -75.6139972
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1021
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 215
                     },
                     "end_location" : {
                        "lat" : 45.4234192,
                        "lng" : -75.6301824
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCyrville Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 128\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "gcftGbcplMe@hCa@`COj@GZO~@_@hCId@CN{@rEEPYzAG`@I`@CJAFYxAKn@]dBUpA?@CJADAFIb@CPEXADMp@_@|BU|AAHId@CRI`@QlAOz@[pBG^Id@o@|DG^G^E^EX"
                     },
                     "start_location" : {
                        "lat" : 45.4201993,
                        "lng" : -75.617935
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.3 km",
                        "value" : 2345
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 486
                     },
                     "end_location" : {
                        "lat" : 45.44307,
                        "lng" : -75.6409213
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eCummings Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "kwftGrorlMICG?GBC@CBICEAC?A@I@I@IDeAf@a@RMFa@P{At@[NGBk@XUJIFUR[Rk@^SLSLs@\\QH_CfAa@P{Ar@QFo@ZSJkA`@mB|@cBr@aBt@gBv@eAb@_A`@g@TGBiBx@WL]NuAn@q@ZaAb@{Ar@eBr@iAf@gAd@sB~@iBz@C@q@XcEjBqIrD{IzD}@`@g@VSHMFC@i@VcBx@WJ]Pe@Tg@V"
                     },
                     "start_location" : {
                        "lat" : 45.4234192,
                        "lng" : -75.6301824
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 165
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 66
                     },
                     "end_location" : {
                        "lat" : 45.4436275,
                        "lng" : -75.6389839
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eMontréal Rd\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa 34\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "erjtGvrtlMOq@Qq@AIGWEOI]I]EU?O@O?CI[Ia@G[I]"
                     },
                     "start_location" : {
                        "lat" : 45.44307,
                        "lng" : -75.6409213
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.9 km",
                        "value" : 1934
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 394
                     },
                     "end_location" : {
                        "lat" : 45.4581478,
                        "lng" : -75.6440037
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAviation Pkwy N\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "uujtGrftlMURm@`@cAt@q@l@{@x@[\\MV[`@OVCBWZc@l@g@z@U`@QZIFYn@a@~@O`@IPGTKVo@nBgAvCSd@g@~@Wb@g@p@WZONSTo@h@GBqAz@cBbAe@VA?_@Pg@Rg@Pg@POBa@Ja@HC?_@FK@E?_AHg@DE?_@@[@sAAq@Cs@Gg@GA?q@MQCWGm@Qe@OUKq@Y]QECUUIEs@e@GEoA_AaBgAYQIG_@YGGGGIIcAs@QAIG[U[U[W[UOMKI[U]UOOGGECCAE?EAC@A?C?EBC@CDSp@CJCLAD"
                     },
                     "start_location" : {
                        "lat" : 45.4436275,
                        "lng" : -75.6389839
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "15.3 km",
                  "value" : 15338
               },
               "duration" : {
                  "text" : "54 mins",
                  "value" : 3220
               },
               "end_address" : "901 Prince of Wales Dr, Ottawa, ON K2C 3K1, Canada",
               "end_location" : {
                  "lat" : 45.3877384,
                  "lng" : -75.7095782
               },
               "start_address" : "11 Aviation Pkwy, Ottawa, ON K1K 2X5, Canada",
               "start_location" : {
                  "lat" : 45.4581478,
                  "lng" : -75.6440037
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 119
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 21
                     },
                     "end_location" : {
                        "lat" : 45.4579724,
                        "lng" : -75.64549599999999
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003eAviation Pkwy\u003c/b\u003e",
                     "polyline" : {
                        "points" : "mpmtG~eulM?DAJAJ?L@J@LHx@NbBDp@BT"
                     },
                     "start_location" : {
                        "lat" : 45.4581478,
                        "lng" : -75.6440037
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 145
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 45.4567254,
                        "lng" : -75.6450148
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eAviation Pathway\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iomtGjoulMr@OnAWbASJCFEHEFGHM"
                     },
                     "start_location" : {
                        "lat" : 45.4579724,
                        "lng" : -75.64549599999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "19 m",
                        "value" : 19
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.4565744,
                        "lng" : -75.64513119999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eAviation Pathway\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qgmtGhlulM^V"
                     },
                     "start_location" : {
                        "lat" : 45.4567254,
                        "lng" : -75.6450148
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.5 km",
                        "value" : 2455
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 402
                     },
                     "end_location" : {
                        "lat" : 45.4568593,
                        "lng" : -75.6740762
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eAviation Pathway\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qfmtG`mulME^ANCNE\\Kv@G`@M|@Gb@Kl@Q|@CNCJADGVIRELGRMXOb@_@r@]h@c@r@c@p@]h@o@pAOV[f@[h@Wb@Ub@_@z@Yr@K^GPYfAo@~BQr@Ox@M~@It@GjAEh@?j@?l@@j@Db@J~@JhABNHt@Dt@Dp@@~@?T?X?PAJCf@?\\@VDZJb@Pn@FVBP@\\Bh@DdAFz@B^HbA@X@J?b@@t@?r@@j@@p@B`@DVBNF`@Jh@b@zAD\\Fb@\\zA`@`BJ\\DTDXF`@BTDTLh@DTFXDV@HL`AFr@HbABx@?v@?~@Ah@El@CXC^AN?P?N@L@P@LDPDVDRDX?@D`@FXBXRvABRDT@LFV@FBFBNFPHVHPR`@Xl@Nb@Jj@BL@J@FBV?X@R?PA\\Ct@Cd@?TAJ@P@P@PBPBRDNDLDTDRDL@H@H@NB`@B`@BV@F"
                     },
                     "start_location" : {
                        "lat" : 45.4565744,
                        "lng" : -75.64513119999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 45.4567459,
                        "lng" : -75.67405049999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e toward \u003cb\u003eSir George-Étienne Cartier Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "khmtG~a{lMTE"
                     },
                     "start_location" : {
                        "lat" : 45.4568593,
                        "lng" : -75.6740762
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.7 km",
                        "value" : 1690
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 356
                     },
                     "end_location" : {
                        "lat" : 45.4504788,
                        "lng" : -75.6863219
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSir George-Étienne Cartier Pkwy\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ugmtGxa{lMBP?TBz@@p@@PBb@F|A@PD`AD~@?F@f@?FB^HzB@ZB`B@`@Cx@?ZAVA^?DEb@AFEZETMf@_@~@]z@GNITERCJCRCTAV?R@L?H@d@BZ@\\AX?TAV@V?F?BBPBN@FH\\Ld@J^P^V~@DN@FFVFZJj@Lj@@DVfA@@DLPb@NXP\\JL\\b@PTZ\\BBJPHJLTPZNV@Dt@bAV\\LPZ^d@d@TVHLFHDFBFHRHVDRHb@DVDNDNDJDHFHDFBB@@DDFFFDJDF@B@F@F?H@F?DAHAHATKRIPMJGFEJGDEPOPQh@i@DEd@o@X]LKb@a@@AZWRMVM`@QVIXMRKPMJKLKRU"
                     },
                     "start_location" : {
                        "lat" : 45.4567459,
                        "lng" : -75.67405049999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 572
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 80
                     },
                     "end_location" : {
                        "lat" : 45.4462431,
                        "lng" : -75.68925589999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "o`ltGnn}lMLz@Jf@DLNXVd@HJPL^Jb@DZJ\\T\\VNLRRJV@HDTLh@JZJRTXXV\\PVHTDR@H@R@D?T?L?TAd@A\\A\\F\\F~@T@@VHJDF?JEHE"
                     },
                     "start_location" : {
                        "lat" : 45.4504788,
                        "lng" : -75.6863219
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 110
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 45.4454232,
                        "lng" : -75.68969969999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003ePrincess Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 93\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_fktGz`~lMBJBBV\\ZJPH^PZPJFB?HW"
                     },
                     "start_location" : {
                        "lat" : 45.4462431,
                        "lng" : -75.68925589999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 232
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 74
                     },
                     "end_location" : {
                        "lat" : 45.4447296,
                        "lng" : -75.69235639999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePrincess Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 93\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{`ktGrc~lMLNNPBBBBDHJPFHBFFPDLDPF^DPBNFZBRBV@RFjAH~ACL?B?@AD@d@"
                     },
                     "start_location" : {
                        "lat" : 45.4454232,
                        "lng" : -75.68969969999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 941
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 202
                     },
                     "end_location" : {
                        "lat" : 45.4371982,
                        "lng" : -75.6974907
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit onto \u003cb\u003eSussex Dr\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eOttawa Regional Rd 93\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "q|jtGft~lMAB?B?D?B?B?B?@@B?@@@@@?@@@@@@@B?@@B?RPDD@@D@JFJDLDDBF@|@d@f@XRJdAj@bAh@|@d@bAl@h@ZFBHDJD\\PNHbAn@FFBBdBbAPH`CtAHBd@XHFj@\\HFPHr@`@VLJDBN?@@@@B^T@@BDNJJDf@V|@f@nBdALFRLTL"
                     },
                     "start_location" : {
                        "lat" : 45.4447296,
                        "lng" : -75.69235639999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 860
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 192
                     },
                     "end_location" : {
                        "lat" : 45.43829969999999,
                        "lng" : -75.7071742
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eEntering Quebec\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "omitGht_mMFb@@DBD@BDFHFHJJJHJHDJBJDFBFFDHJP?@BFDDHHHDHFFJDDDFHPDJBN@T?RCPCPe@nCq@fDqApHMv@_ApFe@rCiA`Hi@fDIn@EFGF"
                     },
                     "start_location" : {
                        "lat" : 45.4371982,
                        "lng" : -75.6974907
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "89 m",
                        "value" : 89
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 45.4390244,
                        "lng" : -75.7067809
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e toward \u003cb\u003eRte Verte 1\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eVoyageurs Pathway\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ktitGxpamMOAWCYGUIYOMGCCACIU"
                     },
                     "start_location" : {
                        "lat" : 45.43829969999999,
                        "lng" : -75.7071742
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 959
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 173
                     },
                     "end_location" : {
                        "lat" : 45.4311109,
                        "lng" : -75.7077767
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eRte Verte 1\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eVoyageurs Pathway\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{xitGjnamMB?B?L@`@JLBLDH@B?BAHCPMPMHCJC@?DA@?D?D@n@VDBh@XB@LFPFPFHBF?F@H?LALADARGFCTAR?N@\\HHBB?JB`@BT@TBtABR@L@PBLDBBHH?@HLDH\\ZPNJX@BB@B@D?\\CHAL?H?DB^RH@H@JAb@CROh@s@FKZm@HMHGFC@AHABANAB?H@NDLFJJXZNVFNBFHDDBDBF?H?LAJAD?\\SBAFAJAR@J@NJHH@@BDB@FD@@B?DBB?B?F?VG"
                     },
                     "start_location" : {
                        "lat" : 45.4390244,
                        "lng" : -75.7067809
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "67 m",
                        "value" : 67
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 45.4305833,
                        "lng" : -75.70737319999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eRte Verte 1\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eVoyageurs Pathway\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "mghtGrtamMFGJIRSFGHILIFCHCNG"
                     },
                     "start_location" : {
                        "lat" : 45.4311109,
                        "lng" : -75.7077767
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1085
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 217
                     },
                     "end_location" : {
                        "lat" : 45.42416160000001,
                        "lng" : -75.7133693
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eRte Verte 1\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eVoyageurs Pathway\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "cdhtG`ramMJCLCHAJAN?L?T@F@B?HBTDDBFBJFDBHFRN\\PTHTDJ@BAHANEPINSHODMHe@H[JY@AVc@h@a@JILITEXCV@\\@NDNDTFJDPLFHDBNN|@~@^h@TZHHJLTPTV\\Z@BFFDJDHBFVf@f@jA@DTf@@BNf@@@Ld@@DNn@FTDT?BHp@Dd@?FBf@@F?@@t@B|@?`@@XBX?@DPFL@@DDDFRVFHFJDJ@B@B@D@F?F@B?P@D?H?D@R@D@LHZ@DHTHT?@FLFNFH"
                     },
                     "start_location" : {
                        "lat" : 45.4305833,
                        "lng" : -75.70737319999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 497
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 106
                     },
                     "end_location" : {
                        "lat" : 45.4244565,
                        "lng" : -75.71954319999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eRte Verte 1\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eVoyageurs Pathway\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow Rte Verte 1\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_|ftGpwbmM?F?B?FAHGHIHIJGJEJAH?F?^?@AxAA\\?R?DC^EdAIrC?PAFCNAFAHALAJ?Z?LARDb@Fz@Dr@D^FdABR@J@J?^@D?ZAZ?VATARAXAJ?RAF?D?H?DABCD"
                     },
                     "start_location" : {
                        "lat" : 45.42416160000001,
                        "lng" : -75.7133693
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.8 km",
                        "value" : 818
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 277
                     },
                     "end_location" : {
                        "lat" : 45.4182076,
                        "lng" : -75.7159394
                     },
                     "html_instructions" : "Take the crosswalk\u003cdiv style=\"font-size:0.9em\"\u003eEntering Ontario\u003c/div\u003e",
                     "polyline" : {
                        "points" : "{}ftGb~cmMIJA?A@C@A@ABABOTVA~@EzBKVIPCJAVGLEPKPI~BkAb@UTMRQlAo@|BsAd@YPKBAJEJCDCNILGd@U^STMTQFCFEHGLMPQDEh@i@DGb@e@LGNGfAgAZ]ZY"
                     },
                     "start_location" : {
                        "lat" : 45.4244565,
                        "lng" : -75.71954319999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.2 km",
                        "value" : 1152
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 202
                     },
                     "end_location" : {
                        "lat" : 45.4117732,
                        "lng" : -75.72422349999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eOttawa Riv Pathway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTrans Canada Trail\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "yvetGrgcmMHR?FCHKPGTGZ?d@@TD\\Jb@BNJ^j@`CRt@FVDDNDHJBFBPFRFXHXHRHLLRNTJNT\\@BNPPRTRTNJDB@^FD@^BB@Z?T@L?b@Ab@IXG|@[b@MXGn@GV?Z?P?L?^F|@NLBHDHBDD@?HJFHFJLNFJFFHHHFJHFFFHDFv@zANXDLFNBLHTHb@H`@BTJz@BPD`@@JJdAFj@Hj@Hn@RtA@JFX"
                     },
                     "start_location" : {
                        "lat" : 45.4182076,
                        "lng" : -75.7159394
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.2 km",
                        "value" : 2154
                     },
                     "duration" : {
                        "text" : "7 mins",
                        "value" : 412
                     },
                     "end_location" : {
                        "lat" : 45.39705319999999,
                        "lng" : -75.70902529999999
                     },
                     "html_instructions" : "Slight \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTrillium Pathway\u003c/b\u003e",
                     "maneuver" : "turn-slight-left",
                     "polyline" : {
                        "points" : "qndtGj{dmMB?@?@@B@@@BB@B@B@FDXDXFVFR?@DHBFBBB@B@B?B?@?DCNGHG\\Q@?NKJK@AHGNMHKHKHOFMZs@\\w@HQHSJ]DOPg@Rq@La@DKDKLSHKBE~@kBl@cAl@eAZk@Xm@Re@Pg@N_@N[^u@N[HQFMDGFELKLKHGHMJM?AFIFGDELIFGDEHIJMBE\\i@T]LUPYXa@HOLSR_@Tk@Rg@Rg@Xk@l@cAp@mAr@gAz@oAf@u@b@s@b@y@R_@Re@Xc@NO^q@NWP]P[FKFEB?B?D?F@DBB?B?BABAJGn@i@XW^Y^YdAy@RORKXMTIJENI`Ag@bAk@^Sh@[b@YRKn@[vAs@|BgAzBiApDsB`Ai@"
                     },
                     "start_location" : {
                        "lat" : 45.4117732,
                        "lng" : -75.72422349999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 230
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 98
                     },
                     "end_location" : {
                        "lat" : 45.3952203,
                        "lng" : -75.7077019
                     },
                     "html_instructions" : "Take the crosswalk",
                     "polyline" : {
                        "points" : "qratGl|amM\\QLIJEHCVIVMZOj@[\\SRO^]XUTSX[VW"
                     },
                     "start_location" : {
                        "lat" : 45.39705319999999,
                        "lng" : -75.70902529999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 557
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 190
                     },
                     "end_location" : {
                        "lat" : 45.39046829999999,
                        "lng" : -75.7075067
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003ePrince of Wales Dr\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRoute 73 S\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cgatGbtamMFF@@f@b@HJDHh@d@HHFDFDFBJBNDLBPDDCDAT?VAbAAf@?bAAl@AN?LAFAHALCLC?APENGXKh@SVKHE`@OTKRIZO`@Cb@QRIBCDCBABAD?H?LBLA"
                     },
                     "start_location" : {
                        "lat" : 45.3952203,
                        "lng" : -75.7077019
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 251
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 68
                     },
                     "end_location" : {
                        "lat" : 45.3891916,
                        "lng" : -75.7100861
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e1st\u003c/b\u003e exit onto \u003cb\u003eNational Capital Commission Scenic Driveway\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "mi`tG|ramM@@@@@??@@?@??@@?HJHDHFFFDHHPFB|@tCDJ^nAHVfAnD"
                     },
                     "start_location" : {
                        "lat" : 45.39046829999999,
                        "lng" : -75.7075067
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "12 m",
                        "value" : 12
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 45.3890821,
                        "lng" : -75.71011519999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at \u003cb\u003eMaple Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ma`tG`cbmMTD"
                     },
                     "start_location" : {
                        "lat" : 45.3891916,
                        "lng" : -75.7100861
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "90 m",
                        "value" : 90
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 13
                     },
                     "end_location" : {
                        "lat" : 45.3886601,
                        "lng" : -75.7111058
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "w``tGfcbmMb@tAn@nB"
                     },
                     "start_location" : {
                        "lat" : 45.3890821,
                        "lng" : -75.71011519999999
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "25 m",
                        "value" : 25
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 3
                     },
                     "end_location" : {
                        "lat" : 45.3884617,
                        "lng" : -75.7109509
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "c~_tGlibmMNMVQ"
                     },
                     "start_location" : {
                        "lat" : 45.3886601,
                        "lng" : -75.7111058
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "4 m",
                        "value" : 4
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 1
                     },
                     "end_location" : {
                        "lat" : 45.3884773,
                        "lng" : -75.7109088
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{|_tGlhbmMCG"
                     },
                     "start_location" : {
                        "lat" : 45.3884617,
                        "lng" : -75.7109509
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "83 m",
                        "value" : 83
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 11
                     },
                     "end_location" : {
                        "lat" : 45.38786899999999,
                        "lng" : -75.710359
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_}_tGdhbmMx@o@BC?@@?B?HCXSDEDI@GBK"
                     },
                     "start_location" : {
                        "lat" : 45.3884773,
                        "lng" : -75.7109088
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "58 m",
                        "value" : 58
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 10
                     },
                     "end_location" : {
                        "lat" : 45.388092,
                        "lng" : -75.709699
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "ey_tGvdbmM?I?Gk@qB"
                     },
                     "start_location" : {
                        "lat" : 45.38786899999999,
                        "lng" : -75.710359
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "38 m",
                        "value" : 38
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 45.3877994,
                        "lng" : -75.7094379
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qz_tGr`bmMx@s@"
                     },
                     "start_location" : {
                        "lat" : 45.388092,
                        "lng" : -75.709699
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "13 m",
                        "value" : 13
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 2
                     },
                     "end_location" : {
                        "lat" : 45.3877384,
                        "lng" : -75.7095782
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wx_tG~~amMJZ"
                     },
                     "start_location" : {
                        "lat" : 45.3877994,
                        "lng" : -75.7094379
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "omftGz_amMd@f@tA|DjCcCvApErAjE`CpHXhAHdDg@rGXtCxCrFrE|BjBfCvEfL_FjA|Be@lA`BnAbEfBtChAzB~Bx@bAt@lApArBbFx@dHtAdHd@fAhAe@vDuGxIgRrDcG|EaHfHqMbCcEl@iAk@oBg@_Cw@}DuD_R}FoOm`@qmA_GkRo@qBdBsCb@c@h@fBAP`@nDr@`CcBtA}AnAwBhBqExDsJbI}JfImB`Bl@tBl@hBX~@l@lBy@p@gBtAaEfDiAhAuDzCe@^~@tCtBnGl@vBrBvG|F~T]`EkBdFuJbH_MxDoBLkAi@_D}IgGuFaEkAiFo@}@ImB{@Cs@_@}ASq@\\a@DcAJ}B}@Bg@hAcAN}BdBy@Zs@y@tAgEbJg]|AwHt@sJLyF\\eFpC{BzHyGrCeClAqCtAsCdC{BnCiKxBuGH}BYw@^wC`C}G~@wAfF_M{@aA_@a@?YU[Hx@Qd@~@cAEUlGcMfFeZrDgPjGkSpNiH~CeCbAsDOaFWsDCmAf@y@vBGLu@]qLw@{ADqGv@_PZaGLiBj@LV}@l@oAtBsEdAsCkAsIAs\\n@wKhFo_@bC_P~@cA`K_GhSeQlF{Zx@sFlBWDsCyAsEiEoTYo@m@FwB~@Ys@]w@@tBjA~IAr@j@xCiAh@GpAv@vE}CrAcIpEyD|@iBoD_KgV{Nye@kAuDsBsG}Al@eClAsGxC_[jN{BZ}@~BiAhG{CdQ{B`MoFx\\w@z@qCdAgQdJs^~O_w@j]qGzCmAl@a@cBYoAi@qD_@IqBvAwC|CiDdFeCtF{GnNiIlFkLnB_Io@_FyB_OcKsDqBe@tBL`BTtCv@DfDu@z@C{@xG_AfEiE~H_FrJwC|Ml@xUnAjQJxGlBlJrClRJ`MrB|J`ApEGrE|@fH\\|ANdE\\fJ?rHgBpGUbJhC|KfFrJdGzJfBdCbFoCtIsGr@zAbAxAjEdCzB|DhCTnFj@dBr@dC~@r@tAt@~KPj@x]xRpGdErF`EfA`AxBlCkLns@cCs@x@GvA]pARvBz@dBQnI|@pAdBnBRbAA`B}B~@a@hBfBfAHnB?`@T|DeBfFzAzAcAnBmDrCCnDbDhFhIzAzLpAnEj@rDLnAc@`Be@jOb@xMc@zBFRzDQlAW~F}CdM_HpCmCnCgCEv@R~EjBnFnAdD|B`ClCRdHmAzDd@~@jA|BjD~@xEbBrK`AjC|CkChHiP~GiMbDiEnNuVdD}Fn@K|KgHt[qP`FeDz@i@`B~A|Al@vGM~GuBxDs@xF|NxB|DpAmAh@UPc@?Qk@qBx@s@JZ"
         },
         "summary" : "Wellington St/Ottawa 34",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : [ 0, 1, 2, 3, 4 ]
      }
   ],
   "status" : "OK"
}

```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
