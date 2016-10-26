# OOAD-WEEK10
Sequence Diagram

#Shopping Online

Code

@startuml

title "Shopping Online"


User -> computer : Open computer

computer -> keyboard : Input password

keyboard -> monitor : Show desktop

computer -> webshopping : Find and Shoping online

User -> webshopping : conferm order \nand Paybills

Company -> User : Wait for Product


@enduml

 
                                    PIC 1 Shopping Online
                                          

![](http://www.plantuml.com/plantuml/img/LP112y8m38Nl-HN1ktzW1n44mPC34IzUkZLgMPUKDcFitviE77Wej7dlvNtqMDHbdSO8e44ZuUxsaPG2l_7ACJ3j0E1UAEF-WBsCQLAxDtXDnDiRDi5C0osTkEpDT66ROdAbp98zR8gvHk6WKZTPtuoUog2I_XRDr9KVIuFdm1wTdSfNHxBYRMp_xbxuHNb4gpNvoJNOkgKBCHOuMOdZfQRMT8CF5nHVXjDcyLEl04TYRx_o1G00)



#Pizza Deliverly

Code

@startuml

title "Pizza Deliverly"


User->phone : Input Password

phone->touchscreen : Input number

User->CallCenter : Contact Service department

CallCenter->Pizzadelivery : conferm order \nand Preparation

Pizzadelivery->User : check order \nand Paybills


@enduml



                                    PIC 2 Pizza Deliverly
                                    
                                    
                                    
![](http://www.plantuml.com/plantuml/img/LP2n3eCm34HtVuN5pWzqG4XqwOPKTUiI4bT43Gvo31LyVGDLMx7Qz-xEhfCQqMa80Eer41QjNrU3Pmf-9WbB0G2tH59MOn-Py8GN7YV5rgJqYk80zdbPQPnidwmGyK_4qz2HV0qQ4q93h2HPq4HMOnMl9BEtX8x6N6J8Qu2_iApsEkxJPicSZVmW6J17Pvyx6tROoWORzP413a1PRT4RrfDz7Y6pT3w4bE-hYLr-mHi0)




#Hotel

Code

@startuml

title "Hotel"


Me->receptionist : To contact for room

receptionist->computer : Insert data and Check Empty room

computer->system : System processes

system->computer : Show data empty room

computer->receptionist : Check Number empty room \nand Details

receptionist->Me : Check in


@enduml




                                    PIC 3 Hotel
                                    
                                    
                                    
![](http://www.plantuml.com/plantuml/img/RP2z3i8m38HtFuNLlI_0K5K291ZAKaQMa1ereechs1NgsnCKVYisIxxlVBvQr4IT_02WJWV2OiTAGm403PLL94kZEWvE55TuPBGSr5Z52qUCp1xWMrDMblquASMatWUXgDWPDMX2X-kUx1MtVjJvYRx4PIMpAFa4jNaO8riI8G78gn_djkTRzgM_RelO-V1XykT4VmWyXKUi3QbnWomVQUXDkf3gg2bqgQSx)




#7 ELEVEN

Code

@startuml

title "7 ELEVEN"


Me->Product : select from product

Me->Cashiers : drop Shipping

Cashiers->Cashautomation : scan bacode

Cashautomation->system : check bacode

system->monitor : Show price details

Me->monitor : Check details from lists product

Me->Cashiers : Pay and Receive product


@enduml




                                    PIC 4 7ELEVEN
                                    
                                    
                                    
![](http://www.plantuml.com/plantuml/img/TP31YW8n38RlVOhWVSw2Xq6GkRaY2dlFjj49spP3azd5jz-kLUVaBVpVH_YJhHeMcrDqpjWYmMeDmtxu70uhvzm7TVsnI9YzmGQK8jNXKYJ1rDAcx517fgBL2KKcE8yyJPolpZr9St0sIMWi-N-RnmnVw2LGynRQzNfJerGjFvB_VcajxleacKrAvUTHVciPzWI133bggxGOk_k61spb8wlfsnEEU0FC0KxaYNzeyToMSgYl-WC0)




#Trip Hong Kong

Code

@startuml

title "Trip Hong Kong"


Me->GroupFriend : select from trip

GroupFriend->GroupTour : Contact Details

GroupTour->TravalCompany : Check Group Tour \nand Conferm Tour

Travelcompany->Guide : Supply Guide for Travel

Travelcompany->BusTour : Supply Bustour for Travel

Guide->Bustour : Details for travel time

Guide->GroupTour : Explain attractions

Guide->Me : Check number of people

Grouptour<-Bustour : Come back group tour \nand end trip

@enduml





                                    PIC 5 Trip Hong Kong
                                    
                                    
                                    
![](http://www.plantuml.com/plantuml/img/PP7BQWCn34Nt_WgH_Vn0AI4qVK78ghFinfbeKbFRChOSah-l_60oq8snfNFrkDubrf6piqgnOOkm6QC9y4d-0WSvDagf8mxRZqWvl4U3_WnFaD3Yn317Si32AxNATtYa70NTasSjx2koDZPriYI7xHZrLTizkQ3zlR0_EFr21Q3AlxsMVb9YnkXgIAaYGZiraVJAveoY_SeXs3kqvqmH6lUFVycfJzOL4k0IM6jgbSfoO_lq5U8A0Hk72xdU-EqMh3OUD0iviI6V5kw8ove-knD6e1a2Kh3OdIaDduT7Pt47uQH5SAc-yCENyXVD_PrSvG__0000)



