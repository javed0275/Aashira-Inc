# Aashira-Inc
Developing Amazon connect contact center for Aashira Inc


We seek to engage a service provider to create and implement a Hosted IVR using Amazon Connect, tailored to our specific needs as follows:

    Amazon Connect IVR Development: The Supplier will construct the Hosted IVR on Amazon Connect, ensuring multilingual support for both English and Spanish.
    Voice User Interface (VUI) Design: Working collaboratively with Aashira Inc., the Supplier will craft a VUI for the Hosted IVR that mirrors the experience defined      for the current on-premise system.
    
    Prompt Integration: The Supplier will integrate pre-recorded WAV file prompts, provided by Aashira Inc., for static messaging within the IVR call flows.
    Dynamic Data Playback: Utilizing Amazon Connect's Text-to-Speech (TTS) capabilities, the system will dynamically convey information like street names, house       numbers, and numeric data to callers in a voice selected by Aashira Inc.
    
    Reporting and Analytics: Integration with an on-premise dashboard will be established to monitor and report on the IVR's performance.
    API Integration: The Supplier will link the Hosted IVR with Azure-based APIs provided by Aashira Inc. for automated outage reporting and self-service.
    Amazon Connect Contact Flows: Building upon Amazon Connect's capabilities, the Supplier will implement contact flows to handle:

        Identification: Callers can be identified through multiple methods, leveraging APIs to authenticate based on phone number, account number, or address.

        Outage Reporting: Callers can report outages directly through the IVR, with the system handling 'total' or 'partial' reports, and other types routed to the on-premise system if necessary.

        Outage Status: Updates on reported outages will be made accessible to callers.

        Customer Preferences: Incorporating a preferences management system, allowing customers to select their language and opt-in for notifications.

    Natural Language Understanding (NLU): The initial greeting will employ a Natural Language-styled approach, similar to the on-premise IVR, to interpret caller intents using Amazon Connect's NLU features.
    Intent Transfer: Should the Hosted IVR be unable to resolve an outage-related intent, the call will be seamlessly transferred to the on-premise IVR, maintaining the continuity of the caller's experience.
    Data Preservation: As calls are transitioned to the on-premise system, all relevant data will be transferred using SIP Headers over a secure connection.
    Project Management: Comprehensive project management services will be provided throughout the implementation of the Hosted IVR solution.

Enhanced Features for Amazon Connect Implementation

    Generative AI for Text-to-Speech: During call transfers, the system will leverage generative AI to provide real-time text-to-speech conversion, ensuring that dynamic content such as updates or notifications are communicated clearly in the caller’s preferred language.
    Access to Recent Interactions: Agents will have immediate access to the last ten recorded interactions for any given customer. This feature allows for a quick review of previous interactions to ensure continuity and a personalized service experience.
    Training Document Recommendations: The IVR will be equipped with the capability to recommend relevant training documents to customers, based on the context of their queries. This self-help feature aims to empower customers to resolve common issues efficiently.
    Custom Widget for Important Information: A custom-built widget will be integrated into the agent’s interface to display critical customer information prominently. This will guide agents through screen prompts, enabling them to provide more focused and informed assistance.
    Speech-to-Text and Interaction Summarization: The system will include speech-to-text functionality, enabling the automatic transcription of conversations. Post-call, the IVR will categorize and create a summarized wrap-up record, improving the ease of follow-up and quality assurance processes.

