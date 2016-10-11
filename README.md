<h1>Project with 2 types of test - ITest and simple test.</h1>
Configure maven to run build without ITests. Create profile to run build with ITests, only ITests. 

1) run test without ITest.java by default.<br />
2) <b>mvn clean test -P run-itest</b> - to execute only ITest.java<br />
3) <b> mvn clean test -P allTests</b> - to execute all existing tests.<br />
