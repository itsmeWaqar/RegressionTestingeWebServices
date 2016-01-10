# RegressionTestingeWebServices
On Model Based Regression Testing of Web Services

Regression testing is helpful in finding out if the quality of an evolved system has not regressed during
maintenance. In case of web services, it becomes an issue since access to implementation is restricted to
interface level information only. The problems gets further complicated if the testing is manual and the
effect of maintenance is minimal. We can establish an idea about the depth of changes through the analysis
of exposed interface and provide test oracle by storing test data and returned values in case of successful
test cases. This paper proposes an interface analysis approach where we analyze these interfaces written in
web service description language (WSDL). We utilize data collected form interface analysis to invoke
service operations and develop test oracles. We use these test oracles for regression testing to ensure there
is no regression in the operations where the interface has not changed. In case, the interface has changed,
we can detect by rerunning interface analysis to find out evolution in the signature
