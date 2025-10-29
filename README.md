⚙️ Workflow You Implemented:

1. Created and configured Nexus repositories — one for release and one for snapshot artifacts.
2. Configured Maven’s pom.xml to define project details and repository deployment rules.
3. Configured settings.xml with authentication credentials to securely connect Maven with Nexus.
4. Built and deployed artifacts using the command mvn clean deploy.
5. Maven automatically determined which repository to upload to (based on the version — SNAPSHOT or Release).
6. Nexus authenticated the request and successfully stored the artifact.
