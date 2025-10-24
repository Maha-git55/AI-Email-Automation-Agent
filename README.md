# AI Email Automation Agent 🤖📧

An intelligent n8n workflow that automatically sends emails to customers using natural language commands through Google Gemini AI.

## 🌟 Overview

This AI-powered automation allows you to send emails by simply typing natural commands like:
- **"Send email to John"**
- **"Email Sarah about project update"**
- **"Contact Michael regarding meeting"**

The AI agent automatically finds customer email addresses from Google Contacts and sends emails through Gmail.

## 🚀 Features

- **Natural Language Processing**: Understands conversational commands
- **AI-Powered Intelligence**: Google Gemini model for context understanding
- **Auto Contact Discovery**: Automatically finds customer emails from Google Contacts
- **Gmail Integration**: Direct email sending through Gmail API
- **Context Memory**: Maintains conversation history and context
- **Zero-Code Setup**: Fully configured n8n workflow

## 🛠️ Workflow Architecture

### Nodes Configuration:
1. **Chat Trigger** - Receives natural language commands
2. **AI Agent** - Processes commands with Google Gemini brain
3. **Tools Integrated**:
   - **Send Message in Gmail** - Email composition and sending
   - **Get Many Contacts in Google Contacts** - Contact lookup

### AI Agent Components:
- **Brain**: Google Gemini Model
- **Memory**: Simple Memory for context retention
- **Tools**: Gmail + Google Contacts integration

## 📋 Setup Instructions

### Prerequisites
- n8n instance (local or cloud)
- Google Cloud Console account
- Gmail API enabled
- Google Contacts API enabled
- Google Gemini API access

### Installation Steps

1. **Import Workflow**
   - Download `first-AI-Agent.json`
   - Import into your n8n instance

2. **Configure APIs**
   - Set up Google Cloud credentials
   - Enable Gmail API
   - Enable Google Contacts API
   - Configure Gemini API

3. **Authentication**
   - Set up OAuth2 for Gmail
   - Configure Google Contacts access
   - Add Gemini API key

4. **Test Workflow**
   - Use chat interface with customer names
   - Verify email sending functionality

## 🎯 Usage Examples

### Example 1: Direct Name Command
**Input**: "Send email to John"  
**Action**: 
- Finds John's email in Google Contacts
- Composes and sends default email

### Example 2: Detailed Request
**Input**: "Email Sarah about the project deadline extension"  
**Action**:
- Locates Sarah's contact information
- Sends contextual email about project deadlines

### Example 3: Specific Instructions
**Input**: "Contact Michael regarding tomorrow's meeting schedule"  
**Action**:
- Finds Michael's email
- Sends meeting-related email

## 💡 Use Cases

- **Customer Support**: Automated response system
- **Sales Teams**: Quick customer follow-ups
- **Marketing**: Campaign email automation
- **Internal Communications**: Team notification system
- **Personal Assistant**: Automated email management

## 🔍 Testing Results

The workflow successfully demonstrates:
- ✅ Natural language understanding
- ✅ Automatic contact lookup
- ✅ Email composition and sending
- ✅ Contextual memory retention
- ✅ Multi-tool integration

## 📄 License

This project is open source and available under the MIT License.

**Built with ❤️ using n8n and Google Gemini AI**
 




## 📁 Project Structure
