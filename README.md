# n8n Workflows

## 📅 Calendar Assistant Workflow

**File:** `workflows/calendar-agent.json`  
**Description:**  
This workflow uses an **AI Agent** connected to **OpenAI GPT-4o-mini** and **Google Calendar**.  

- Listens for chat messages (`Chat Trigger`)
- AI Agent processes intent with `OpenAI Chat Model`
- Checks availability and creates events via Google Calendar  

**Timezone:** Asia/Kolkata  
**Status:** Not active by default (`"active": false`) — activate after import in n8n.

### 🚀 Deploy
1. Import workflow in n8n (`Settings → Import from file`).
2. Reconnect credentials (OpenAI + Google Calendar).
3. Activate the workflow.
