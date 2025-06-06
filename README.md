# MCP Inspector Arxiv Chatbot 📚

Hello, people jan! 🤗
Let's now build our MCP server, run locally and test our tools with a friendly UI from the MCP Inspector.
Hope my comments along the code will be helpful. 

To do it locally on your own: 

### 1. Clone & Install

First, make sure you have Python 3.9+ installed.

```bash
git clone git@github.com:Armiyants/mcp-inspector-arxiv-chatbot.git
cd mcp_inspector_arxiv_chatbot
python3 -m venv venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
```

### 2. Run the MCP Server

Start the server locally:

```bash
npx @modelcontextprotocol/inspector python mcp_server.py
```

Follow the link and open the MCP Inspector UI in your browser.

---

## Using the Inspector UI

### Step 1: Connect
- Click the **Connect** button to start the connection to your MCP server.
- ![Connect Screenshot](https://drive.google.com/uc?export=view&id=1iBb7yDXELNU4C-s6CRk96ukG7SSqL28d)

### Step 2: Explore  and Run Tools
- Go to the **Tools** tab at the top.
- Click **List Tools** to see all available tools.
- Select a tool (e.g., `get_arxiv_papers` or `extract_info`). You will now see all the input arguments for each tool.
- Fill in the input fields (like `topic` or `paper_id`).
- Click **Run Tool** to execute and see the results.
- ![List, Explore and Run Tool](https://drive.google.com/uc?export=view&id=1DIcBbQLN8xhdFie0yP3aNZTpo8wrQBdU)

---

## Project Structure
- `mcp_server.py`: Main server code and tool definitions.
- `requirements.txt`: Python dependencies.
- `variables.py`: Configuration (edit as needed).

---

## Tips
- You can always restart or disconnect the server from the UI sidebar.
- Check the **History** panel to see your previous actions and results.

---

## Wanna contribute ? Need Help?
If you get stuck, just ask!
And feel free to submit issues and enhancement requests!
Enjoy the journey ~ ☺️
