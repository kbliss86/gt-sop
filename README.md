# GrapeTree SOP Bot

The **GrapeTree SOP Bot** is an advanced RAG (Retrieve, Augment, Generate) bot designed to assist users within the GrapeTree organization by providing advice, knowledge, instructions, and direct links to Standard Operating Procedures (SOP) documents. This bot leverages Azure Cognitive Services for document indexing, alongside Teneo.AI and ChatGPT to deliver contextual and conversational responses based on user queries.

> **Note**: This project was a proof of concept that was never deployed due to a lack of ROI, high costs associated with Azure Cognitive Services, and challenges in maintaining and updating the indexed documents.

## Key Features

- **Document Retrieval**: Uses Azure Cognitive Services to index and retrieve relevant SOP documents based on user inquiries.
- **Knowledge Augmentation**: Enriches responses with additional context and advice using Teneo.AI, enhancing the knowledge available in the SOP documents.
- **Response Generation**: Employs ChatGPT to generate helpful and natural language instructions or advice, tailored to user queries.
- **Direct Links to SOPs**: Provides users with direct access to relevant SOPs, ensuring that they can review official procedures as needed.
- **Organization-wide Assistance**: Supports users across the GrapeTree organization, offering insights and guidance on various internal procedures.

> **Important**: Links to SOPs are hosted within the GrapeTree 365 Tenant and are not clickable outside of that environment. To explore functionality, ask the chatbot:  
> `"Can you summarize for me how to increase HCP engagement?"`

-**HCP** is an acronym only used within GrapeTree - so the bot must rely on the documenation provided in the index to explain, Bot is limited to responses to the medical staffing feild

## Technologies Used

- **Azure Cognitive Services**: Indexes and retrieves SOP documents for easy access during user interactions.
- **Teneo.AI SDK**: Provides the conversational framework for understanding user queries and offering relevant guidance.
- **ChatGPT API**: Generates informative and personalized responses, improving overall user experience.
- **JavaScript, Groovy Script, CSS**: The underlying technologies powering the chatbot interface and backend logic.

## Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/grapetree-sop-bot.git
    ```

## How It Works

1. **Retrieve**: The bot first retrieves relevant SOP documents by indexing them with Azure Cognitive Services, ensuring the most relevant information is found.
2. **Augment**: Using Teneo.AI, the bot augments this information with additional context or procedural advice, ensuring clarity and comprehensiveness.
3. **Generate**: Finally, ChatGPT generates conversational, easy-to-understand instructions or advice based on the retrieved and augmented data, delivering it to the user in real-time.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
