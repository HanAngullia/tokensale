# Fantom Foundation FTM whitelisting lottery

[FANTOM Whitelisting Lottery Overview](https://medium.com/fantomfoundation/fantom-whitelisting-lottery-overview-363c4275c677)

## Stage 1 Lottery Inputs

The lottery data is in [lottery_1_input.txt](https://github.com/Fantom-foundation/tokensale/blob/master/lottery/lottery_1_input.txt)

SHA256 hash = 208a6b65b503ba3eab58348053afca240040518c0dffd94466a4847417250162

https://etherscan.io/tx/0x5eed1f62bf05452602ab7886e18762110591883e74127e0a9daa3e308426b913

Decision at 12-JUN-2018 @ 17:00 UTC -- corresponding to NIST beacon at 06/12/2018 7:00 pm (https://beacon.nist.gov/home)

## Stage 1 Lottery Results

The lottery results are in [lottery_1_result.txt](https://github.com/Fantom-foundation/tokensale/blob/master/lottery/lottery_1_result.txt)

Here is the NIST beacon value at 06/12/2018 7:00 pm (https://beacon.nist.gov/home):

E7FB52653FDCEC8562C226C14526B8B877AA99AD89D55EBA402BCF70A981E6CD
F4B3A42F2AE2FF68804795B92C01C7534105B66CBDE3767577B2B92394D14C72

The corresponding base 10 number R is:

12149868849766449211901153489073573982487128517210919352090281003926692678537014332180530904275769738130124240289475481025464029755662550987151049132952690

We had n = 84,631 randomly shuffled addresses, and R % 84,631 = 20,220 wich can be seen for example [here](http://www.calculator.net/big-number-calculator.html?cx=12149868849766449211901153489073573982487128517210919352090281003926692678537014332180530904275769738130124240289475481025464029755662550987151049132952690&cy=84631&cp=20&co=mod)

Therefore, the lottery winners are the 6,000 addresses starting at index 20,220 in the original list.

Note that selecting randomly from an ordered list is equivalent to shuffling first and then taking a slice - and this second method can be done more transparently than the first one.

## Stage 2 Lottery Inputs

## Stage 2 Lottery Results