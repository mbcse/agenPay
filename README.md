# AgenPay — Agentic Payment Infrastructure for Web3 Teams(Agentic Stripe for Web3)

**AgenPay** is the first AI-powered crypto payment system where your **agent handles everything** — from scheduling and sending to receiving, refunding, and reconciling payments. Designed for modern workflows, your agent connects directly with your **Notion workspace** and leverages **X402Pay ** to fully automate your crypto payment lifecycle.

https://www.loom.com/share/686e16a92fb14263a1bf6db7d779e761?sid=4edb7e14-9bfd-463a-9ef4-ba2cae42cae7
---

## 🏗️ Technical Architecture

### Core Components

- **🤖 AI Agent System**: LangGraph-powered autonomous payment processing
- **🗃️ Notion Integration**: Direct workspace synchronization for payment operations
- **💳 X402Pay Protocol**: Web3 payment links with cryptographic verification
- **🔐 CDP Wallets**: Secure multi-user crypto wallet management
- **📊 Multi-User Dashboard**: Real-time analytics and transaction monitoring
- **⚡ Real-Time Processing**: Event-driven payment automation

### Technology Stack

**Backend** (`agenpay-backend/`)
- **Node.js + Express.js**: REST API server with authentication
- **LangGraph.js**: AI agent workflow orchestration
- **OpenAI GPT-4**: Natural language payment processing
- **PostgreSQL + Prisma**: Multi-user data persistence
- **Coinbase CDP SDK**: Secure wallet operations
- **JWT**: Stateless authentication
- **Nodemailer**: Email notifications

**Frontend** (`agenpay-frontend/`)
- **React 18**: Modern UI with hooks and context
- **Tailwind CSS**: Responsive design system
- **Axios**: HTTP client for API communication
- **React Router**: Client-side routing

**Integrations**
- **Notion API**: Workspace setup and real-time sync
- **X402Pay Protocol**: Crypto payment link generation
- **Base Network**: Ethereum L2 for fast, cheap transactions

---

## ⚙️ How It Works

### 🧾 Notion-First Interface

Most teams already run operations in Notion — so why switch tools?
AgenPay lets you turn any Notion database into a powerful payment dashboard:

1. **Automated Workspace Setup**: Creates organized payment databases
2. **Real-Time Synchronization**: Agent monitors Notion for changes
3. **Smart Data Extraction**: AI parses natural language entries
4. **Bi-Directional Updates**: Status changes flow between systems

### 🤖 Agent = Your Payment Ops Team

The AI agent automatically watches your Notion for:
- New payment requests
- Overdue invoices
- Subscription renewals
- Refund schedules

And reacts instantly:
- ✅ Schedules recurring payments
- ✅ Sends personalized X402Pay links
- ✅ Follows up on unpaid invoices
- ✅ Reconciles records and marks invoices as "Paid"
- ✅ **Automatically refunds payments** after set time periods

### 🔁 Ask & Refund Flow (Like Stripe Intents)

Automated payment flows with built-in refund logic:

```
Ask 0.1 ETH from john@company.com, refund after 30 days
```

The agent:
1. Creates secure X402Pay payment link
2. Sends personalized email to recipient
3. Updates Notion with payment status
4. Schedules automatic refund
5. Executes refund using CDP wallet

### 💬 Chat-Based Payments

Natural language payment control:

```
User: "Send 50 USDC to alice@startup.com for consulting work"
Agent: ✅ Payment link created and sent. Tracking in Notion.

User: "Ask 0.05 ETH from the team for coffee fund"
Agent: ✅ Processing 3 payment requests. Links sent to all members.
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL database
- OpenAI API Key
- Coinbase Developer Platform account
- Notion integration (optional)

### Setup Process

1. **Clone the repository** and install dependencies for both frontend and backend
2. **Configure environment variables** including database, OpenAI API, and CDP credentials
3. **Initialize the database** with the required schema
4. **Start the application** and access the dashboard
5. **Connect integrations** like Notion workspace and email notifications

### Key Integrations

- **OpenAI API**: Powers the AI agent for natural language processing
- **Coinbase CDP**: Handles secure cryptocurrency transactions
- **Notion API**: Enables workspace synchronization and team collaboration
- **SMTP Email**: Delivers payment notifications and reminders

---

## 🔧 Configuration

### Wallet Integration

**Coinbase Developer Platform (CDP)**
- Real cryptocurrency transactions on Base network
- Secure multi-user wallet management
- Support for ETH, USDC, and other ERC-20 tokens
- Testnet and mainnet compatibility

### Email Integration

**SMTP Configuration**
- Real email delivery for payment notifications
- Personalized payment request templates
- Automated follow-up and reminder systems
- Support for Gmail and other SMTP providers

### Notion Integration

**Workspace Setup**:
1. Create Notion integration at https://notion.so/integrations
2. Add integration to your workspace
3. Configure OAuth credentials in environment

**Features**:
- Automated workspace setup with payment databases
- Real-time payment tracking and synchronization
- Notion database integration for team workflows
- Bi-directional status updates

---

## 🧠 Key Features

### ✨ AI-Powered Processing
- **Natural Language Understanding**: Parse payment requests from plain English
- **Context Awareness**: Maintains conversation history for follow-ups
- **Smart Scheduling**: Handles complex timing requirements
- **Error Recovery**: Graceful handling of failed transactions

### 🔄 Automated Workflows
- **Payment Scheduling**: Recurring invoices and subscriptions
- **Follow-Up Logic**: Automated reminders for overdue payments
- **Refund Automation**: Stripe-style payment intents for crypto
- **Status Synchronization**: Real-time updates across all platforms

### 🔐 Enterprise Security
- **Multi-User Isolation**: Each user gets isolated agent and wallet
- **JWT Authentication**: Stateless, secure session management
- **Wallet Segregation**: Individual CDP wallets per user
- **Data Encryption**: Secure storage of sensitive information
- **TEE**: Agent runs securely in TEE's

### 📊 Real-Time Analytics
- **Payment Tracking**: Comprehensive transaction monitoring
- **Performance Metrics**: Agent efficiency and success rates
- **Financial Reporting**: Automated bookkeeping and reconciliation
- **Custom Dashboards**: Personalized views for different use cases



**Built with ❤️ for the future of Web3 payments** 