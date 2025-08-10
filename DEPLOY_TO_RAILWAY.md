# Deploy NextChat to Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/nextchat)

Deploy your own NextChat AI assistant platform on Railway with one click. NextChat supports multiple AI providers including OpenAI GPT, Anthropic Claude, Google Gemini, and many more.

## 🚀 Quick Deploy

1. Click the "Deploy on Railway" button above
2. Connect your GitHub account
3. Configure your API keys (see below)
4. Deploy and enjoy your AI assistant!

## 🔑 Required Configuration

### OpenAI API Key (Required)
- Get your API key from [OpenAI Platform](https://platform.openai.com/api-keys)
- Add it as `OPENAI_API_KEY` environment variable
- This enables GPT-3.5, GPT-4, and GPT-5 models

### Access Code (Recommended)
- Set `ACCESS_CODE` to secure your NextChat instance
- Leave empty to disable password protection
- Railway will auto-generate a secure code if you don't specify one

## 🤖 Optional AI Providers

### Google Gemini
- Get your API key from [Google AI Studio](https://makersuite.google.com/app/apikey)
- Set `GOOGLE_API_KEY` environment variable
- Enables Gemini Pro and Gemini Pro Vision

### Anthropic Claude
- Get your API key from [Anthropic Console](https://console.anthropic.com/)
- Set `ANTHROPIC_API_KEY` environment variable
- Enables Claude 3 Haiku, Sonnet, and Opus

## ⚙️ Configuration Options

### Security Settings
- `HIDE_USER_API_KEY`: Hide API key input field (default: true)
- `ACCESS_CODE`: Password protection for your instance

### Model Configuration
- `DISABLE_GPT4`: Disable GPT-4 models (default: false)
- `DEFAULT_MODEL`: Set default AI model (default: gpt-3.5-turbo)
- `CUSTOM_MODELS`: Define custom model list (JSON format)

### API Settings
- `BASE_URL`: Custom OpenAI API endpoint (for proxies)
- `OPENAI_ORG_ID`: OpenAI organization ID
- `ENABLE_BALANCE_QUERY`: Show API balance (default: true)

### Advanced Features
- `ENABLE_MCP`: Enable Model Context Protocol (default: true)
- `DISABLE_FAST_LINK`: Disable quick sharing (default: false)

## 📱 Features

### Multi-Provider Support
- **OpenAI**: GPT-3.5, GPT-4, GPT-5
- **Anthropic**: Claude 3 Haiku, Sonnet, Opus
- **Google**: Gemini Pro, Gemini Pro Vision
- **DeepSeek**: DeepSeek Chat, DeepSeek Coder
- **Moonshot**: Moonshot v1
- **ByteDance**: Doubao models
- **Baidu**: ERNIE models
- **And many more!**

### Advanced Capabilities
- **Model Context Protocol (MCP)**: Extend AI capabilities with tools
- **Vision Models**: Image understanding with GPT-4V, Gemini Vision
- **Code Generation**: Specialized coding models
- **Real-time Chat**: WebRTC audio conversations
- **Export/Import**: Save and share conversations
- **Plugin System**: Extend functionality
- **PWA Support**: Install as mobile/desktop app

## 🔧 Environment Variables Reference

| Variable | Description | Required | Default |
|----------|-------------|----------|---------|
| `OPENAI_API_KEY` | OpenAI API key for GPT models | ✅ Yes | - |
| `ACCESS_CODE` | Password for instance access | Recommended | Auto-generated |
| `GOOGLE_API_KEY` | Google Gemini API key | No | - |
| `ANTHROPIC_API_KEY` | Anthropic Claude API key | No | - |
| `BASE_URL` | Custom API base URL | No | - |
| `HIDE_USER_API_KEY` | Hide user API key input | No | `true` |
| `DISABLE_GPT4` | Disable GPT-4 models | No | `false` |
| `DEFAULT_MODEL` | Default AI model | No | `gpt-3.5-turbo` |
| `ENABLE_MCP` | Enable MCP support | No | `true` |

## 🚨 Troubleshooting

### Common Issues

**"API key not working"**
- Verify your API key is correct and has sufficient credits
- Check if you're using the right provider's key
- Ensure no extra spaces in the environment variable

**"Access denied"**
- Make sure you set the correct `ACCESS_CODE`
- Try clearing browser cache and cookies

**"Models not loading"**
- Verify your API keys are valid
- Check if you have access to the specific models
- Some models require special access (e.g., GPT-4)

**"Deployment failed"**
- Check Railway logs for specific error messages
- Ensure all required environment variables are set
- Verify your GitHub repository access

### Getting Help
- Check [NextChat Issues](https://github.com/ChatGPTNextWeb/NextChat/issues)
- Railway Support: [Railway Help](https://help.railway.app/)
- Community: [NextChat Discussions](https://github.com/ChatGPTNextWeb/NextChat/discussions)

## 🔄 Updates

Your NextChat deployment will automatically update when you push changes to your connected GitHub repository. Railway will rebuild and redeploy automatically.

## 💰 Cost Estimation

Railway Pricing:
- **Hobby Plan**: $5/month with generous usage limits
- **Pro Plan**: $20/month with higher limits
- Usage-based pricing for compute and bandwidth

AI API Costs (separate):
- **OpenAI**: Pay per token usage
- **Anthropic**: Pay per token usage  
- **Google**: Free tier available, then pay per use

## 🛡️ Security Best Practices

1. **Always set ACCESS_CODE** to protect your instance
2. **Use environment variables** for all API keys
3. **Enable HIDE_USER_API_KEY** to prevent API key exposure
4. **Regularly rotate** your API keys
5. **Monitor usage** to prevent unexpected charges

## 📋 Next Steps

After deployment:

1. Visit your Railway app URL
2. Enter your access code (if set)
3. Start chatting with your AI assistant
4. Explore different models and providers
5. Configure MCP tools for enhanced capabilities
6. Customize settings to your preference

Enjoy your personal AI assistant powered by NextChat on Railway! 🎉