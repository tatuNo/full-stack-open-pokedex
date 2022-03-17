I chose Java as the language as it is most familiar to me.

**Linting:** Checkstyle seems to be one of the most popular linting tool. Other great candidates are PMD & SonarLint, 
although these are used more for finding potential problems, possible bugs, unused and suboptimal code, over-complicated expressions and duplicate code.
**Testing:** JUnit is one of the most widely adopted open source unit testing frameworks. TestNG is another popular open source unit testing framework, and many others provide more specific purposes.
EasyMock/Mockito/JMockit provide mocking and DbUnit can be useful when testing databases.

**Building:** For automating build process most popular tools seems to be Maven and Gradle. Gradle introduces a Groovy-based domain-specific language instead of the XML
form used by Maven of declaring the project configuration.

Jenkins seems to be most popular due to its flexibility and powerfulness. Other widely used CI tools are Buddy,
TeamCity and Bamboo CI.

As the project is relatively small (team size 6 members), i would imagine that cloud-based solution fill our needs.
Set up would be easier and i think that in small project we would find service that provide enough support.
When using cloud-based CI team wouldn't need to worry about server maintenance or applying software updates/patches.
Eventually our project budget and requirements would guide us which option offers the right tradeoffs.