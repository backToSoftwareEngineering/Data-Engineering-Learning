# My Daily Learning Log 📚

Welcome to my daily learning log for data engineering! This space is dedicated to documenting my progress, key learnings, challenges faced, and solutions discovered.

---

## Recent Entries
* **[2025-08-27] Git Repository Synchronization & Python Deep Dives**
  * **Repository Synchronization**
    * Resolved `fatal: refusing to merge unrelated histories` error when syncing local IC3 project with GitHub.
    * Cause: local and remote repositories had no common history.
    * Solution: used `git pull origin main --allow-unrelated-histories` to merge, then `git push -u origin main` to upload files.
    * Gained deeper understanding of Git internals, branch histories, and synchronization best practices.
  * **Python Fundamentals & Advanced Concepts**
    * Function Encapsulation: refined scraping/parsing logic into reusable functions for modularity and readability.
    * List Transformation: used `map()` to transform lists (e.g., int → str) and contrasted it with object methods in other languages.
    * List Comprehensions: clarified syntax for filtering (`if` at end) vs. conditional assignment (`if/else` inside expression).
    * Data Scaling: distinguished normalization (0–1 range) vs. standardization (mean=0, std=1) for numeric data.
    * Underscore `_`: learned Python convention for unused loop variables.
    * Advanced Slicing & Ellipsis (`...`): explored `...` as a concise slicing shortcut in multi-dimensional arrays (e.g., NumPy).
      
* **[2025-08-10] Advanced Web Scraping & Function Encapsulation**
  *  Encapsulating complex logic into reusable functions, handling multiple tables with different HTML schemas, and passing data between functions.

* **[2025-08-08] Web Scraping with BeautifulSoup & Pandas**
  *  IC3 Annual Report Data Scraper (https://www.ic3.gov/AnnualReport/Reports/2016State/#?s=1)
  *  Requests for fetching HTML, BeautifulSoup for HTML parsing, handling tables with complex structures, and the process of converting scraped data into a pandas DataFrame.
    
* **[2025-08-06] Python for Data - Pandas Basics**
    *  Basic data manipulation, reading CSVs.
    *  
* **[2025-07-15] ERD Fundamentals & Practice: Car Dealership Case**
    *  Crow's Foot notation, entity identification, relationships (1:1, 1:M, M:N), optionality.
    *  Disentangling ambiguous text for `Skill` and `MachineType` relationships.

* **[2025-07-09] SQL Joins and CTEs Deep Dive**
    *  Inner, Left, Right, Full Joins; Common Table Expressions for complex queries.
    *  Optimizing multi-join queries for performance.
   
---

