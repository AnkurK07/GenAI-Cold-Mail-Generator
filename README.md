# GenAI-Cold-Mail-Generator
![image](https://github.com/user-attachments/assets/441d5287-af4b-42cf-b74d-873f3ffbb513)

### Problem Statement 
Service companies often face challenges in effectively reaching potential clients or partners with personalized communication. Crafting tailored cold emails requires significant time and effort, especially when aligning with specific job opportunities or business needs. Additionally, extracting relevant job listings and presenting portfolio links that resonate with a company’s requirements can be cumbersome and prone to generic outreach, leading to low engagement rates.

### Solution
Cold Mail Generator for Services Companies
A dynamic tool built with Groq, LangChain, and Streamlit to craft personalized cold emails for service companies. This generator extracts job listings directly from a company’s careers page and creates tailored emails that feature relevant portfolio links sourced from a vector database.

### Use Case Example:
![image](https://github.com/user-attachments/assets/35d12925-3d29-4c0d-b5af-65b57f26c5d4)

Imagine Cyberdyne Systems, a leader in advanced robotics, is actively searching for a Principal Software Engineer to lead a critical AI project. The company is dedicating substantial time and resources to the hiring process, including screening, onboarding, and training suitable candidates.

On the other side, John Conner, a business development executive from Skynet.AI—a cutting-edge software development company—sees an opportunity to offer Cyberdyne an immediate solution. Using the Cold Mail Generator, John inputs the URL of Cyberdyne’s careers page. The tool swiftly extracts the Principal Software Engineer job listing, analyzes the job requirements, and generates a highly personalized cold email.

This email not only addresses Cyberdyne’s specific hiring needs but also highlights a skilled software development engineer from Skynet.AI who perfectly matches the job description. The email includes relevant portfolio links sourced from a vector database, demonstrating Skynet.AI’s expertise in AI and robotics.

By leveraging the Cold Mail Generator, John can streamline Cyberdyne's recruitment process, save their time and resources, and establish a strategic partnership, all through a single, impactful outreach email.

## Architecture Diagram
![image](https://github.com/user-attachments/assets/75570621-e862-4bad-b32a-4fe2dc4c2e85)

# Project Structure

- **`Chains/`**: Contains modules for constructing and managing processing chains.
- **`Experiments/`**: Includes Jupyter Notebooks for testing and experimentation.
- **`Resources/`**: Stores portfolio data for personalized emails.
- **`load_portfolio/`**: Handles portfolio data loading and preprocessing.
- **`utils/`**: Provides utility functions for the application.
- **`vectorstore/`**: Stores vector database files for portfolio retrieval.
- **`app.py`**: Main Streamlit app to run the tool.
- **`requirements.txt`**: Lists dependencies for the project.
