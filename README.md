[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/enogrob/ebook-project/master)
```
Roberto Nogueira  
BSd EE, MSd CE
Solution Integrator Experienced - Certified by Ericsson
```
# eBook Grails in Action

![ebook image](assets/ebook.png)

**About**

Learn everything you need to about the subject of this `eBook` project.

[Homepage](https://www.manning.com/books/grails-in-action-second-edition)

## Topics
```
FOREWORD
PREFACE
ACKNOWLEDGMENTS
ABOUT THIS BOOK
ABOUT THE TITLE
ABOUT THE COVER ILLUSTRATION
PART 1 INTRODUCING GRAILS
READ IN LIVEBOOK
1. GRAILS IN A HURRY…​
[ ] 1.1. Introducing Grails
[ ] 1.1.1. Why Grails changed the game
[ ] 1.1.2. Seven big ideas
[ ] 1.2. Getting set up
[ ] 1.3. QOTD: your sample program
[ ] 1.3.1. Writing a controller
[ ] 1.3.2. Generating an HTML page: the view
[ ] 1.3.3. Adding style with Grails layouts
[ ] 1.4. Creating the domain model
[ ] 1.4.1. Configuring the data source
[ ] 1.4.2. Exploring database operations
[ ] 1.5. Adding UI actions
[ ] 1.5.1. Scaffolding: adding rocket fuel
[ ] 1.5.2. Surviving the worst-case scenario
[ ] 1.6. Improving the architecture
[ ] 1.6.1. Your Grails test case
[ ] 1.6.2. Going Web 2.0: Ajaxing the view
[ ] 1.6.3. Bundling the final product: creating a WAR file
[ ] 1.6.4. And 80 lines of code later
[ ] 1.7. Summary and best practices
READ IN LIVEBOOK
2. THE GROOVY ESSENTIALS
[ ] 2.1. Writing your first script
[ ] 2.1.1. Using lists, loops, and methods
[ ] 2.1.2. Working with strings
[ ] 2.2. Creating a quote analyzer class
[ ] 2.2.1. Introducing Spock properly
[ ] 2.2.2. Creating the initial class
[ ] 2.2.3. Working with maps
[ ] 2.2.4. Taking the analyzer for a spin
[ ] 2.3. Going to the next level
[ ] 2.3.1. Discovering closures
[ ] 2.3.2. Programming dynamically
[ ] 2.3.3. To type or not to type
[ ] 2.4. Summary and best practices
PART 2 CORE GRAILS
READ IN LIVEBOOK
3. CMODELING THE DOMAIN
[ ] 3.1. Introducing the Hubbub sample application
[ ] 3.1.1. Domain-driven design
[ ] 3.1.2. Hubbub kick-start: from 0 to first hit
[ ] 3.1.3. Introducing GORM
[ ] 3.2. Your first domain class object
[ ] 3.2.1. Saving and retrieving users via tests
[ ] 3.2.2. Updating user properties
[ ] 3.2.3. Deleting users
[ ] 3.3. Validation: stopping garbage in and out
[ ] 3.3.1. Standard validators
[ ] 3.3.2. Custom validation with regular expressions
[ ] 3.3.3. Cross-field validation tricks
[ ] 3.3.4. Keeping validation DRY by importing constraints
[ ] 3.4. Defining the data model — 1:1, 1:m, m:n
[ ] 3.4.1. One-to-one relationships
[ ] 3.4.2. One-to-many relationships
[ ] 3.4.3. Many-to-many relationships
[ ] 3.4.4. Self-referencing relationships
[ ] 3.5. Summary and best practices
READ IN LIVEBOOK
4. CREATING THE INITIAL UI
[ ] 4.1. Creating instant UIs with scaffolding
[ ] 4.1.1. Scaffolding Hubbub’s domain classes
[ ] 4.1.2. Improving the validation
[ ] 4.2. Restyling the scaffolding
[ ] 4.2.1. Changing the skin you’re in
[ ] 4.2.2. Branding your pages
[ ] 4.3. Working with the scaffolding code directly
[ ] 4.3.1. Customizing the dynamic scaffolding
[ ] 4.3.2. Scaffolding as a starting point
[ ] 4.4. Summary and best practices
READ IN LIVEBOOK
5. RETRIEVING THE DATA YOU NEED
[ ] 5.1. Setting up the data and search form
[ ] 5.1.1. Loading sample data
[ ] 5.1.2. Implementing the search
[ ] 5.2. Writing Where queries
[ ] 5.2.1. The query syntax
[ ] 5.2.2. Exploring Where queries
[ ] 5.3. When Where queries aren’t suitable
[ ] 5.3.1. Cheap and cheerful listing and counting
[ ] 5.3.2. Introducing Criteria queries
[ ] 5.3.3. Dynamic queries with criteria
[ ] 5.3.4. Creating a tag cloud using report-style query projections
[ ] 5.3.5. Using HQL directly
[ ] 5.4. Summary and best practices
READ IN LIVEBOOK
6. CONTROLLING APPLICATION FLOW
[ ] 6.1. Controller essentials
[ ] 6.2. Implementing a timeline for Hubbub
[ ] 6.3. Testing controller actions: an introduction to mocking
[ ] 6.3.1. About unit tests
[ ] 6.3.2. @TestFor and @Mock mixins
[ ] 6.3.3. Applying @TestFor and @Mock
[ ] 6.4. From controller to view
[ ] 6.4.1. Creating the view
[ ] 6.4.2. Adding new posts
[ ] 6.5. Exploring scopes
[ ] 6.5.1. Request scope
[ ] 6.5.2. Flash scope
[ ] 6.5.3. Session scope
[ ] 6.5.4. servletContext (application) scope
[ ] 6.6. Handling default actions
[ ] 6.6.1. One test, two use cases
[ ] 6.6.2. Working with redirects
[ ] 6.7. Summary and best practices
READ IN LIVEBOOK
7. SERVICES AND DATA BINDING
[ ] 7.1. Services: making apps robust and maintainable
[ ] 7.1.1. Implementing a PostService
[ ] 7.1.2. Wiring PostService to PostController
[ ] 7.2. Data binding
[ ] 7.2.1. Action argument binding
[ ] 7.2.2. Binding to an existing object
[ ] 7.2.3. Working with blacklist and whitelist bind params
[ ] 7.2.4. Complex forms: binding multiple objects
[ ] 7.2.5. Error handling
[ ] 7.3. Command objects
[ ] 7.3.1. Handling custom user registration forms
[ ] 7.3.2. Participating in injection
[ ] 7.4. Working with images
[ ] 7.4.1. Handling file uploads
[ ] 7.4.2. Uploading to the filesystem
[ ] 7.4.3. Rendering photos from the database
[ ] 7.5. Intercepting requests with filters
[ ] 7.5.1. Writing your first filter
[ ] 7.5.2. Testing filters
[ ] 7.5.3. Filter URL options
[ ] 7.6. Creating custom URL mappings
[ ] 7.6.1. myHubbub: rolling your own permalinks
[ ] 7.6.2. Optional variables and constraints
[ ] 7.6.3. Handling response codes and exceptions
[ ] 7.6.4. Mapping directly to the view
[ ] 7.6.5. Wildcard support
[ ] 7.6.6. Named URL mappings
[ ] 7.7. Summary and best practices
READ IN LIVEBOOK
8. DEVELOPING TASTY FORMS, VIEWS, AND LAYOUTS
[ ] 8.1. Understanding the core form tags
[ ] 8.1.1. A handful of essential tags
[ ] 8.1.2. A pocketful of link tags
[ ] 8.1.3. A tour of the form tags
[ ] 8.1.4. Adding pagination to the timeline
[ ] 8.2. Extending views with your own tags
[ ] 8.2.1. Simple tags
[ ] 8.2.2. Testing taglibs
[ ] 8.2.3. Logical tags
[ ] 8.2.4. Iteration tags
[ ] 8.2.5. Calling one tag from another
[ ] 8.3. Adding delicious layouts
[ ] 8.3.1. Introducing SiteMesh
[ ] 8.3.2. Standardizing page layouts
[ ] 8.3.3. Markup fragments with templates
[ ] 8.3.4. Adding skinning
[ ] 8.3.5. Implementing navigation tabs
[ ] 8.4. Applying Ajax tags
[ ] 8.4.1. Choosing a JavaScript library
[ ] 8.4.2. Essential Ajax form remoting
[ ] 8.4.3. Adding sizzle: animation and effects
[ ] 8.5. Summary and best practices
PART 3 EVERYDAY GRAILS
READ IN LIVEBOOK
9. BUILDING RELIABLE APPLICATIONS
[ ] 9.1. Running tests
[ ] 9.1.1. Mastering test execution
[ ] 9.1.2. Choosing a test phase
[ ] 9.2. Understanding Grails unit tests and mocks
[ ] 9.2.1. Mocking core Grails artifacts
[ ] 9.2.2. Mocking normal collaborators with Spock
[ ] 9.3. Testing the application as a whole
[ ] 9.3.1. Introducing browser-based testing with Geb
[ ] 9.3.2. Understanding how Geb works
[ ] 9.3.3. Using page objects for maintainability
[ ] 9.4. Summary and best practices
READ IN LIVEBOOK
10. USING PLUGINS: JUST ADD WATER
[ ] 10.1. Taking advantage of others' hard work
[ ] 10.1.1. Finding plugins
[ ] 10.1.2. Installing plugins via the (deprecated) install-plugin command
[ ] 10.1.3. Installing plugins via BuildConfig.groovy
[ ] 10.1.4. Plugin dependencies
[ ] 10.1.5. Applying your knowledge: the Hubbub extreme makeover begins
[ ] 10.2. Adding mail support
[ ] 10.2.1. Sending mail inline
[ ] 10.2.2. Using a view as your mail body
[ ] 10.2.3. Testing mail operation
[ ] 10.3. Caching for performance: making everything snappy
[ ] 10.3.1. The core caching annotations
[ ] 10.3.2. Working with the CacheManager API
[ ] 10.3.3. Leveraging other members of the Cache plugin family
[ ] 10.3.4. The cache taglibs: caching in the view
[ ] 10.4. Database migrations: evolving a schema
[ ] 10.4.1. Installing and configuring the plugin
[ ] 10.4.2. Establishing a baseline
[ ] 10.4.3. Implementing common migrations
[ ] 10.4.4. Groovy-based migrations
[ ] 10.5. Full-text search: rolling your own search
[ ] 10.5.1. Making objects searchable
[ ] 10.5.2. Highlighting hit terms
[ ] 10.5.3. Implementing pagination
[ ] 10.5.4. Customizing what gets indexed
[ ] 10.5.5. Query suggestions: did you mean "Grails"?
[ ] 10.5.6. Searching across relationships
[ ] 10.6. Summary and best practices
READ IN LIVEBOOK
11. PROTECTING YOUR APPLICATION
[ ] 11.1. Dealing with untrusted data and networks
[ ] 11.1.1. Validating user input
[ ] 11.1.2. Data binding
[ ] 11.1.3. Escaping output
[ ] 11.1.4. CSRF and form tokens
[ ] 11.1.5. Protecting your data in transit
[ ] 11.2. Access control
[ ] 11.2.1. What is it and what can we use?
[ ] 11.2.2. Getting started with Spring Security
[ ] 11.2.3. Protecting URLs
[ ] 11.2.4. Getting hold of the current user
[ ] 11.2.5. Using a custom login page
[ ] 11.2.6. Testing access control
[ ] 11.3. Further exploration of Spring Security
[ ] 11.3.1. Tightening restrictions on access
[ ] 11.3.2. Social authentication
[ ] 11.4. Summary and best practices
READ IN LIVEBOOK
12. EXPOSING YOUR APP TO OTHER PROGRAMS
[ ] 12.1. Creating a REST interface
[ ] 12.1.1. What is REST?
[ ] 12.1.2. Implementing a quick API
[ ] 12.2. Improving the API
[ ] 12.2.1. Handling data representations
[ ] 12.2.2. Customizing the controller
[ ] 12.2.3. Reporting errors
[ ] 12.3. Securing and maintaining the API
[ ] 12.3.1. Configuring API security
[ ] 12.3.2. Versioning the API
[ ] 12.3.3. Implementing functional testing
[ ] 12.4. Summary and best practices
READ IN LIVEBOOK
13. SINGLE-PAGE WEB APPLICATIONS (AND OTHER UI STUFF)
[ ] 13.1. Revisiting Grails web resource management
[ ] 13.1.1. Defining your resources
[ ] 13.1.2. Using resource modules in your view tier
[ ] 13.2. RESTful clients with AngularJS
[ ] 13.2.1. Configuring your Grails app for AngularJS
[ ] 13.2.2. Your first AngularJS controller: pulling in a RESTful timeline
[ ] 13.2.3. Creating a new post via REST
[ ] 13.2.4. Communicating between controllers
[ ] 13.2.5. Better posting with live UI feedback
[ ] 13.3. Advanced RESTful CRUD: implementing in-place editing
[ ] 13.3.1. Implementing UI switching
[ ] 13.3.2. Introducing an update feature
[ ] 13.3.3. Finalizing lifecycles with delete
[ ] 13.4. Summary and best practices
READ IN LIVEBOOK
14. UNDERSTANDING SPRING AND TRANSACTIONS
[ ] 14.1. Spring fundamentals
[ ] 14.1.1. What is dependency injection?
[ ] 14.1.2. Beans by convention
[ ] 14.1.3. Customizing an application at runtime
[ ] 14.2. Using transactions with GORM
[ ] 14.2.1. Easy transactions with services
[ ] 14.2.2. Transactions, the session, and me
[ ] 14.2.3. Fine-grained transactions
[ ] 14.3. Summary and best practices
PART 4 ADVANCED GRAILS
READ IN LIVEBOOK
15. UNDERSTANDING EVENTS, MESSAGING, AND SCHEDULING
[ ] 15.1. Lightweight messaging with Platform Core
[ ] 15.1.1. Installing Platform Core
[ ] 15.1.2. Sending off an event
[ ] 15.1.3. Listening for an event
[ ] 15.1.4. Using namespaces to integrate GORM and events
[ ] 15.1.5. Aggressive listening: using wildcards
[ ] 15.1.6. Integrating Spring Security using the grailsEvents bean
[ ] 15.2. A hitchhiker’s guide to JMS messaging
[ ] 15.2.1. Learning to think in async: identifying messaging candidates
[ ] 15.2.2. Messaging terminology: of producers, consumers, queues, and topics
[ ] 15.2.3. Installing and configuring the JMS plugin
[ ] 15.3. Using the Grails JMS plugin
[ ] 15.3.1. Our killer Hubbub feature: IM integration with Jabber
[ ] 15.3.2. Sending JMS messages
[ ] 15.3.3. Reading the queue
[ ] 15.4. Scheduling tasks with Grails
[ ] 15.4.1. Writing a daily digest job
[ ] 15.4.2. Fine-grained scheduling with cron
[ ] 15.5. Advanced scheduling
[ ] 15.5.1. Dealing with re-entrance and stateful jobs
[ ] 15.5.2. Pausing and resuming stateful jobs programmatically
[ ] 15.5.3. Job persistence with JDBS storage
[ ] 15.6. Summary and best practices
READ IN LIVEBOOK
16. NOSQL AND GRAILS
[ ] 16.1. The problem with PostgreSQL (or when to choose NoSQL)
[ ] 16.2. Types of NoSQL databases (and typical use cases table)
[ ] 16.3. Using Redis to work with key-value stores
[ ] 16.3.1. Installing your own Redis server
[ ] 16.3.2. Using Redis operations
[ ] 16.3.3. Installing the Redis plugin (including pooling configuration)
[ ] 16.3.4. Simple, expiring key/value caching: what is all this @Memoize stuff?
[ ] 16.3.5. Working with the Redis taglib
[ ] 16.3.6. Beyond the basics: working with the Redis service object directly
[ ] 16.3.7. Top posters with Redis sorted sets
[ ] 16.4. Using MongoDB to work with document-oriented data
[ ] 16.4.1. Learning MongoDB terminology16.4.2. Getting set up: installing a MongoDB server
[ ] 16.4.2. Creating your first database
[ ] 16.4.3. Installing the MongoDB plugin
[ ] 16.4.4. Polyglot persistence: Hibernate and MongoDB working together
[ ] 16.4.5. Stepping outside the schema with embeddables
[ ] 16.4.6. Dynamic attributes: making up properties as you go along
[ ] 16.4.7. Querying MongoDB via standard GORM
[ ] 16.4.8. Working with low-level MongoDB querying
[ ] 16.5. Using Neo4j to work with graph-oriented data
[ ] 16.5.1. Installing and configuring the Neo4j plugin
[ ] 16.5.2. Neo4j domain classes: combining with Hibernate
[ ] 16.5.3. Populating Hubbub’s social graph
[ ] 16.5.4. Walking and visualizing the graph with Cypher
[ ] 16.5.5. Walking the entire graph
[ ] 16.6. Summary and best practices
READ IN LIVEBOOK
17. BEYOND COMPILE, TEST, RUN
[ ] 17.1. Getting to deployment
[ ] 17.1.1. Managing your dependencies
[ ] 17.1.2. Continuous integration and deployment
[ ] 17.2. Integrating Grails with Maven
[ ] 17.2.1. Creating a single-project POM
[ ] 17.2.2. Multiproject Maven builds
[ ] 17.3. Grails with Gradle
[ ] 17.3.1. Building a standalone app
[ ] 17.3.2. Building a multiproject app
[ ] 17.4. Summary and best practices
READ IN LIVEBOOK
18. GRAILS IN THE CLOUD
[ ] 18.1. Getting to know the cloud
[ ] 18.1.1. What is the cloud?
[ ] 18.1.2. The new kids on the block — PaaS providers
[ ] 18.2. Running in the cloud
[ ] 18.2.1. Choosing a cloud provider and assessing Hubbub
[ ] 18.2.2. Getting familiar with the platform
[ ] 18.2.3. Adding cache support
[ ] 18.2.4. Sending emails
[ ] 18.2.5. Messaging in the cloud with RabbitMQ
[ ] 18.2.6. Other features to consider
[ ] 18.3. Summary and best practices
BONUS CHAPTERS — AVAILABLE ONLINE
READ IN LIVEBOOK
19. ADVANCED GORM KUNG FU
[ ] 19.1. Domain model kung fu
[ ] 19.1.1. Exploring inheritance options
[ ] 19.1.2. Embedding domain classes
[ ] 19.1.3. Using maps for quick and dirty (or cheap and cheerful) tables
[ ] 19.1.4. Exploring domain model events
[ ] 19.2. Caching kung fu: moving from 2 users to 210
[ ] 19.2.1. Hibernate settings: should you use the second-level cache?
[ ] 19.2.2. Configuring the cache
[ ] 19.2.3. Caching individual domain classes
[ ] 19.2.4. Enough talk, let’s profile: P6Spy
[ ] 19.2.5. Improving performance with indexed fields
[ ] 19.2.6. What about query caching?
[ ] 19.2.7. JNDI? That’s so old school…​
[ ] 19.3. Legacy integration kung fu
[ ] 19.3.1. Recycling Hibernate mappings
[ ] 19.3.2. Using GORM DSL to access existing database table structures
[ ] 19.3.3. Dealing with multiple data sources
[ ] 19.4. Summary and best practices
READ IN LIVEBOOK
20. DEVELOPING PLUGINS
[ ] 20.1. Creating the plugin
[ ] 20.1.1. Are you sure it’s not an application?
[ ] 20.1.2. Controllers, views, and other artifacts
[ ] 20.2. Deepening the integration with Grails
[ ] 20.2.1. Setting up Spring beans
[ ] 20.2.2. Finding out about application artifacts
[ ] 20.2.3. Dealing with class reloading
[ ] 20.2.4. Playing with filters
[ ] 20.3. Publishing your plugin
[ ] 20.3.1. Testing plugins
[ ] 20.3.2. Releasing the plugin into the wild
[ ] 20.4. Summary and best practices
APPENDIX A: GROOVY REFERENCE
[ ] A.1. Operator overloading
[ ] A.2. Groovy JDK methods
APPENDIX B: GORM QUERY REFERENCE
[ ] B.1. Where queries
[ ] B.2. Criteria queries
APPENDIX C: XML AND SPRING BUILDERS
[ ] C.1. XML generation with MarkupBuilder
[ ] C.2. Bean Builder
INDEX
```
