# Railway Deployment Button

Add this button to your README.md to enable one-click Railway deployment:

```markdown
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/nextchat)
```

## Template Configuration

This NextChat template includes:

### ✅ Railway Configuration Files
- `railway.toml` - Service configuration with health checks and volumes
- `.railway/template.json` - Template metadata for Railway marketplace  
- `DEPLOY_TO_RAILWAY.md` - Comprehensive deployment documentation

### 🔧 Key Features
- **One-click deployment** with pre-configured environment variables
- **Health check** using `/api/config` endpoint
- **Persistent storage** for MCP configurations (1GB volume)
- **Security-first** with generated access codes and hidden API keys
- **Multi-provider support** for 20+ AI services
- **Professional presentation** with proper descriptions and documentation

### 🚀 Environment Variables
- Auto-configured with Railway best practices
- Required: `OPENAI_API_KEY`
- Optional: `GOOGLE_API_KEY`, `ANTHROPIC_API_KEY`
- Security: `ACCESS_CODE` with auto-generation
- Features: `ENABLE_MCP`, `HIDE_USER_API_KEY`, etc.

### 📦 Template Submission
To submit this template to Railway:
1. Push these changes to your GitHub repository
2. Visit Railway Dashboard > Templates
3. Submit your repository for review
4. Railway team will review and publish

The template follows all Railway best practices including:
- Professional naming and descriptions
- Proper environment variable documentation  
- Health checks and resource requirements
- Security configurations
- Comprehensive user documentation