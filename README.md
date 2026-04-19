# AOCUM
AOCUM (AI-Oriented Corpus Management System)
Status: Work In Progress (WIP) / Research & Development
Proposed by: ぼちぴ (Bochipi)

Date: April 4, 2026 (Project started: November 29, 2025)

💡 Declaration: To Protect the Sovereignty of Information
In an era where AI determines the "truth" of information, the systematization of knowledge is indispensable.

In Edo era, when the "Black Ships" came to Japan, Japanese leaders made new words and protected our logic. Today, AI is like the digital "Black Ships." If we do nothing, our unique ideas will disappear into the average answers of AI.

AOCUM is a system to build a multi-layered knowledge base. It helps AI agents to understand the "context" and "definitions" of information accurately. We do not just give information to AI. We build a structure to get "recommendations" and "quotes" from AI with our names.

🛠 Problems Solved
Prevention of AI Hallucinations: Minimizing errors through rigorous term definitions.

Protection of "Sovereignty" and Credit: Commanding AI to show the author’s name and article links.

Domain Knowledge Optimization: Ensuring accurate learning of specialized fields.

AI Resource (Token) Optimization: Streamlining reference processes via a structured index.

🏗 Architecture (Methodology)
This system synchronizes the following elements to provide the most "AI-friendly" information structure:

llms.txt: Providing a "Priority Map" (Table of Contents) for AI agents.

Schema.org (JSON-LD): Eliminating ambiguity through structured metadata.

Corpus Dictionary: High-quality linguistic resources optimized for contextual learning.

Glossary: Knowledge graph construction via bidirectional linking of articles and terms.

Automation: Efficient implementation using WordPress (ACF / functions.php), etc.

📊 Reference Implementation (Sample Data)
A minimal structure for linking specific terms with articles for AI interpretation:

JSON
{
  "@context": "https://schema.org",
  "@type": "DefinedTerm",
  "name": "Term Name",
  "description": "Rigorous definition for AI reference",
  "termCode": "Unique-ID-001",
  "inDefinedTermSet": "URL of Glossary",
  "subjectOf": {
    "@type": "BlogPosting",
    "name": "Article Title using this term",
    "url": "Article URL"
  }
}

🌐 Live Implementation
Concrete implementation and testing (focused on "Zen") are active at the following URL: https://s2rz.com/

📜 License
This project is licensed under CC BY-NC-SA 4.0.
© 2026 ぼちぴ (Bochipi)
