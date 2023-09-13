# ticket-list-to-jdk-jira-query

### https://franferrax.github.io/tools/ticket-list-to-jdk-jira-query/

Read ticket numbers from the query string and convert them in a [bugs.openjdk.org](https://bugs.openjdk.org) Jira query.

This is to be used for `@bug` [jtreg](https://openjdk.org/jtreg) headers linking with the following **IntelliJ Idea** [_Issue Navigation Link_](https://www.jetbrains.com/help/idea/settings-version-control-issue-navigation.html):

* Issue ID (regular expression): `(?<=^|[^\w#])(?:@bug )([\d ]+)\b`
* Issue link (replacement expression): `https://franferrax.github.io/tools/ticket-list-to-jdk-jira-query#$1`
