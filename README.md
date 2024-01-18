# nextgenGPTHackathon
AI Research Assistant with GPT-4 Vision
Objective: To create an AI research assistant that aids in drafting research papers by integrating textual and visual data analysis.

Prompt engineering.

Core Features
1. Automated Research Drafting: Utilizing GPT-4's language model to draft sections of a research paper. This includes synthesizing information from various textual sources and generating coherent, contextually relevant content. Prompt engineering - novel.
    1. Content writer: Abstract, Introduction (1500 words), Related Works, Methodology, Results, Discussion, Conclusion.  
        1. Agent - instructed based on the prompt given, style, behavior. 
        2. Supported by guidance to the agent specific APA style.
        3. Search relevant latest research papers 
            1. Google Scholar + Google Search literature - peer-reviewed papers.
            2. Semantic API (200 million papers).
            3. (Not ArXIV, wiki, books).
    2. PDF reader
        1. Upload pdf, read pdf and write contents based on the scanned text.
        2. GPT-4 vision based scanning.
        3. Transcriber - copy and paste text from pdf - may need a library.
    3. RAG implementation
2. Visual Data Analysis: Leveraging GPT-4's vision capabilities to analyze and interpret images. 
        1. This feature is crucial for research papers that involve visual data like charts, graphs, or images from experiments. 
        2. GPT-4 with Vision can process images, identify objects, and even transcribe text from images, making it easier to integrate visual data into research papers​​​​. Upload research photos, heritage photos, existing photos. 
        3. Image-based Query Handling: Users can upload images (like experimental setups, charts, etc.) and ask specific questions. The AI will analyze the image and provide detailed descriptions or answers based on its understanding of the visual content​​.

# License
This is an Unlicence repository. anyone can use, adapt and apply what's (legally) posted there for any purpose, including commercial. Specifically, TaskLife might use it, in totality or parts, as is or with modification, into its commercial software, without any attrribution to nor compensation for the people who created it.
