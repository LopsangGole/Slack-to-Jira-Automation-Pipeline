# Slack-to-Jira-Automation-Pipeline
An automated bug reporting system that integrates Slack with Jira using n8n, reducing manual QA effort and improving reporting consistency.

Demo
https://drive.google.com/file/d/1KIcUvY08IRQCaSyIhcGmSYHlk-84Vo5x/view?usp=sharing


Impact
⏱ Reduced manual ticket creation effort by ~70%
📈 Improved consistency in bug reporting
⚡ Faster communication between QA and developers
🔄 Streamlined QA workflow


Project Structure
/project-root
│
├── workflow.json       # Exported n8n workflow
├── screenshots/        # Slack, n8n, Jira images
└── README.md           # Project documentation


How to Run
1. Import workflow.json into n8n
2. Configure:
    Slack credentials (OAuth)
    Jira API credentials
3. Set Slack Trigger to monitor #bug-report channel
4. Activate workflow
5. Send a message in Slack to test


Future Improvements
🧠 AI-based bug parsing (title, steps, severity extraction)
🔁 Duplicate ticket detection
👤 Auto-assignment based on module
📎 Screenshot/file attachment support
🎛 Slack buttons (Create / Cancel ticket)
