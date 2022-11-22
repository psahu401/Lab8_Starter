# Lab 8 - Starter
1) All, because we can first manually test for edge cases locally, then before pushing, test using automated large volume of test cases and finally at the end of the development cycle (E2E)
2) No
3) No, a unit test should not be used for testing the messaging feature as it would involve various other software functionalites like the network over which it is communicating, the device that is receiving the communication etcetra. 
4) Yes, this can be tested as this is an edge case that would require trying the 'max message length' feature, which would ideally just return with a success under some characters and a failure over some characters.
