# WeChat Reply Copilot

Windows assistant for drafting replies in personal WeChat, with support for legacy `WeChat.exe` and WeChat 4.x `Weixin.exe`.

## Downloads

- [Source package](downloads/wechat-reply-copilot-source-12fa625.zip) - requires Python 3.11. Extract it, run `setup.cmd`, then `start.cmd`.
- [Portable package](downloads/wechat-reply-copilot-portable-12fa625.zip) - self-contained Windows x64 build. Extract it and run `WeChatReplyCopilot\portable-launcher.cmd`.
- [SHA256 checksums](downloads/SHA256SUMS.txt)

The portable build does not require Python. On first use, configure your own model endpoint and API key through the menu.

## Privacy

The downloads do not contain the developer's API key, WeChat database, chat snapshots, drafts, local configuration, or virtual environment. API keys are stored in Windows Credential Manager.

## Verification

```powershell
Get-FileHash .\wechat-reply-copilot-portable-12fa625.zip -Algorithm SHA256
```

The release executable is unsigned, so Windows may show an unknown publisher or SmartScreen warning.
