# How to build the code

1. Run Visual Studio. Open solution using TFLClient.sln

2. Build solution. Menu: BUILD -> Build Solution

# How to run output

1. Build solution, see previous instruction.

2. Go to directory [you solution directory]\RoadStatus\bin\Debug

3. Open RoadStatus.exe.config in test file editor (for example Notepad).

3.1 Setup your TFL ID and KEY following instruction at https://api.tfl.gov.uk

3.2 Provide value for you TFL ID &lt;add key="id" value="YOUR ID" /&gt;

3.3 Provide value for you TFL KEY &lt;add key="key" value="YOUR KEY" /&gt;

4.1 Run RoadStatus.exe a2

4.2 Run RoadStatus.exe a33333

4.3 Run RoadStatus.exe !"£$%^&**&^

# How to run tests

1. Run Visual Studio with TFLClient.sln

2. Open Test Explorer tool window. Menu: TEST -> Windows -> Test Explorer

3. Run test. Menu: TEST -> Run -> All Tests

4. All tests must be green on Test Explorer tool window.

