# 🏛️ ADGM Corporate Agent

> **AI-Powered Legal Document Review for Abu Dhabi Global Market**

An intelligent Streamlit-based application that helps review legal documents for ADGM (Abu Dhabi Global Market) compliance, identifies missing documents, and highlights potential issues using advanced AI capabilities.

## ✨ Features

### 🔍 **Intelligent Document Analysis**
- **Multi-format Support**: Process both DOCX and PDF documents
- **Legal Process Detection**: Automatically identifies the type of legal process (Company Incorporation, Licensing, Employment)
- **Compliance Scoring**: Provides detailed compliance scores (0-100%) based on ADGM requirements
- **Issue Detection**: Identifies critical, high, medium, and low severity issues

### 📋 **Comprehensive Document Review**
- **Missing Document Detection**: Identifies required documents that haven't been uploaded
- **Jurisdiction Validation**: Checks for proper ADGM jurisdiction references
- **Required Clauses Analysis**: Ensures mandatory clauses are present
- **Language Review**: Identifies ambiguous or prohibited language

### 🤖 **AI-Powered Workflow**
- **Multi-Agent Architecture**: Uses LangGraph with specialized agents:
  - **Parser Agent**: Extracts content and metadata
  - **Validator Agent**: Checks completeness and basic compliance
  - **Compliance Agent**: Performs detailed analysis
  - **Output Agent**: Generates annotated documents
- **Groq AI Integration**: Powered by latest Groq models for fast, accurate analysis

### 🔒 **Security & Privacy**
- **Local Processing**: Documents are processed in real-time and not stored
- **API Key Security**: Keys are not saved or transmitted beyond the session
- **File Validation**: Multiple layers of validation for uploaded files
- **Size Limits**: 10MB per file limit with content truncation protection

## 🚀 Quick Start

### Prerequisites
- Python 3.10 or higher
- Groq API key (starts with 'gsk_')

### Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd corporate_agent
