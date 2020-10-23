Approach:
We started by reading through the assignment and making sure that we understood the "Implementing the Router" section. We looked into select() and pull(), then began printing the messages we get when we ran the tests. From seeing the messages we got, we implemented the methods needed for level 1 tests. We then continued to follow the implementation steps to make level-2, 3, 4 and 5 pass. We changed data structures along the way, including routes including extra data, and lookup_routes using longest prefix matching. When we got to level-6 tests, we had to also gain a high level understanding of coalesce and how it works. Once we had that understanding, coalesce just took some time, but was overall not too difficult.


Challenges:
When we first began, it seemed that there was alot to implement all at once. We were a bit lost on where to start coding, but quickly found our footing after printing out json files of the imported messages. We also ran into some problems with pointers when updating certain fields in our routes table.
Overall, our biggest challenge came when implementing dissagregation of coalesces. We initially thought our coalesce was opperation in correctly, but found that our revokes were causing our routing table to not work as intended, which made the dissagregating function incorrectly. We had to take a new approach to implementing revoke, which eventually worked and made our code function as intended.


Testing:
We tested by using the given testing program sim, and using print statements when neccessary. The print statements were added in when we weren't sure exactly what the data looked like at the current state. Also, printing out json formatted files to make sure the packets we sent out were formatted correctly helped alot as well.