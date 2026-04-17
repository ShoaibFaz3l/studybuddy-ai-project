
# -------------------- Project Workflow ----------------------
# 1) User submits a question using Google Form.
# 2) The response is automatically stored in Google Sheets.
# 3) This Python script reads the latest user question from Google Sheets.
# 4) The question is sent to a Large Language Model (LLM) using LangChain.
# 5) LangChain processes the query and generates an intelligent answer.
# 6) The generated answer is displayed in the terminal for monitoring.
# 7) The same AI-generated answer is sent to Google Apps Script via HTTP.
# 8) Google Apps Script saves the answer back into Google Sheets
#    in the corresponding row, completing the sheet automation.
# 9) The question, user details (email, phone), and AI-generated answer
#    are also stored in Supabase (PostgreSQL database) for persistent storage.
# 10) This enables structured data management, future retrieval,
#     analytics, and scalability of the AI system.
# ------------------------------------------------------------
