# Test Task Overview: Python Intern Candidate

## Objective:
As part of this test task, you are expected to conduct research on various web scraping tools and develop a Python script that can extract lead information from LinkedIn. The goal is to scrape details such as name, location, work history/experience, skills, and contact information (email and/or phone number) using location and job title/keyword inputs.

## Tools to Research:
- Bright Data
- Phantombuster
- Apify
- Clay
- Scrapfly
- Any other scraping tools you may find that are useful for the task.

## Task Requirements:

### 1. Research:
- Investigate and evaluate the above-listed tools and any other tools you find that can be used to scrape LinkedIn data. You need to understand their capabilities, limitations, pricing models, and ease of use.
- Focus on how each tool can be utilized to extract data such as name, location, work history, skills, and contact details (email/phone number). Also, explore if these tools support scraping based on location and job title/keyword.

### 2. Data Extraction:
- Your script should be capable of scraping leads based on location and job title/keyword inputs.
- The output should include:
  - **Name**
  - **Location**
  - **Work History/Experience**
  - **Skills**
  - **Email and/or Phone Number**

### 3. Integration:
- If a tool, like Phantombuster, requires LinkedIn profile URLs as inputs, you are expected to find a way to obtain these URLs using another tool, such as a location/keyword scraper.
- You may combine multiple tools to achieve the result if necessary. For example, use one tool to gather LinkedIn profile URLs based on location and job title, and then pass those URLs into another tool (e.g., Phantombuster) to scrape detailed data from those profiles.

### 4. Script Development:
- Write a Python script (or scripts) to automate the scraping process.
- The script should be modular and maintainable. It should allow for dynamic input of location and job title/keywords and should be able to handle different tools in an efficient manner.

### 5. Data Handling and Storage:
- The scraped data should be stored in **CSV format**.
- Ensure that data privacy and ethical guidelines are considered in your approach (e.g., respecting LinkedIn’s terms of service).

### 6. Documentation:
- Document your approach and the tools you used, explaining why each tool was chosen for specific tasks.
- Provide clear instructions on how to run your script and any dependencies required (e.g., libraries, API keys).

## Submission:
- Python code files.
- Python code documentation.
- A brief report outlining:
  - Your research on the tools and how each was used.
  - How the data was obtained and stored.
  - Any challenges faced and how you overcame them.
  - Any relevant findings, such as limitations of the tools or alternative solutions.

## Evaluation Criteria:
- **Research**: Depth of understanding of scraping tools and their application.
- **Problem-solving**: Ability to creatively combine tools to achieve the task.
- **Code quality**: Code readability, modularity, and proper documentation.
- **Data handling**: How well the data is extracted and stored, and adherence to ethical scraping practices.
