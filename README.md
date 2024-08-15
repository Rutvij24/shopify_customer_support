# shopify_customer_support
Project aims to leverage Large Language Models (LLMs) to enhance  customer support interactions by providing intelligent, context-aware responses. It  seeks to seamlessly integrate LLM technology with databases, PDF knowledge bases,  and audio processing agents, creating a comprehensive customer support application.

# Approach
 ## Greeting and Authenticating the Customer:
 - Thesystem starts with a greeting message, welcoming the user to the
 customer support service.
 - Prompt the user to provide their full email address or phone number for
 authentication.
 - Implement an LLM-based edge to validate and authenticate the user input.
 - Uponsuccessful authentication, retrieve user details and subscription
 information.
 ## LLMsasGraphs:
 - Define utility functions for handling system output, user input, and parsing
 information.
 - Create classes for edges and nodes to structure the customer support
 flow as a graph.
 - Implement an edge that checks if the input meets specific conditions (e.g.,
 valid email, phone call request).
 - Parse the validated input to extract relevant information (e.g., email,
 phone number).
 ## NodeOrchestration:
 - Design a node to manage the flow of conversation and orchestrate the
 edges.
 - Gather user input and identify which edge(s) should be followed based on
 conditions.
 - Implement logic to run to continue with the appropriate edge based on
 user input.
 ## EdgeImplementation:
 - Define various edges with specific conditions and parsing queries.
 - UseLLMstoperform checks and parse user input to extract relevant
 information.
 ## Retrieval Augmented on Health Center Data:
 - Create knowledge bases (e.g., premium subscription knowledge base,
 free subscription knowledge base) for context-based retrieval.
 - Implement a multi-retrieval chain to select the appropriate knowledge base
 based on the user's subscription type.
 - Usethechain to retrieve information relevant to user queries.
 ## Call Handling and Summary Generation:
 - Setupacall edge to simulate phone call interactions with the user.
 - Retrieve user information and subscription details from history to initiate
 the call.
 - UseLLMstohandle the call and extract a summary of the conversation for
 ticket generation.
 ## Final App Integration:
 - Integrate all components into a comprehensive customer support
 application.
 - Establish a user interface for interaction, allowing users to engage with the
 application.
