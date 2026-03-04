# Contract testing

## Books
- [O'Reilly books: Contract Testing in Action][8]

## Overviews
- [Pact overview - interactive slides][1]
- [Pact: Introduction to contract testing - Part 1 The problem with end-to-end integrated tests][2]
- [Pact: Introduction to contract testing - Part 2 Contract testing and how Pact works][3]
- [Pact: Introduction to contract testing - Part 3 Demo - Contract testing with Pact JS][4]
- [Pact: Introduction to contract testing - Part 4 How do I remove end-to-end tests?][5]

## Good advice and practical tips
> IMO: This is especially good when you understand the basic concepts, and have seen / written some basic tests
- [Pact: Advanced contract testing with Pact - Best practices for writing consumer tests][6]

Key takeaways:
- [Postels law][7] is a good principle to follow. i.e. Be specific about about you send, and be flexible as to what you recieve
- Contract tests should ONLY focus on the defined interactions between the services
  - i.e. if an ID always has a prefix of "X" but thats not specified in the contract, then don't include that in your tests
- Only write tests for things you consume
- Contract tests help verify "the shape of the data" rather than all the specifics


[1]: https://pactflow.io/how-pact-works/#slide-1
[2]: https://youtu.be/U05q0zJsKsU?si=6B228r4N0nhCcogg
[3]: https://youtu.be/IetyhDr48RI?si=Iiv0pHFc8jC9h4CG
[4]: https://youtu.be/6Qd-kq1AzZI?si=M-VlejVHJDr_F0dP
[5]: https://youtu.be/3T8J8Pwu3I4?si=3qC065Zgdkh6sqbF
[6]: https://youtu.be/oPuHb9Rl8Zo?si=oS6nnXFf0Xs_EFba
[7]: https://lawsofux.com/postels-law/
[8]: https://learning.oreilly.com/library/view/contract-testing-in/9781633437241/
