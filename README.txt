This ZIP-archive contains the following folders and files.

 - Front-end
 - Back-end
 - Appendices.pdf
 - Documentation.pdf

The folders are structured as follows.

# Front-end
Files in the root are configuration files and dependency specifications.
The application source code is located in the folder “app” and is structured as follows.

 - App_Resources, Images and assets for the native platforms
 - nativescript-services, Wrapper services for native functionality
 - shared, Services used across views
 - tests, POC tests

The rest of the folders holds each view.

# Back-end
Files in the root are configuration files and dependency specifications.
The folders and files are structured as follows

 - scripts, the original python data analysis algorithms
 - src, application source code
   - algorithms, data analysis algorithm and mediator
   - data, api layers
     - connectors, database connector logic
     - models, abstraction for resolves to hide database details
     - resolvers, resolver functions for GraphQL resources
     - schema, GraphQL schema definitions
   - smtp, e-mail transmission service
   - server.ts, the main server application
 - test, POC unit and integration tests