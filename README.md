# WhatsApp Claude Plugin

WhatsApp channel plugin for Claude Code — connects WhatsApp as a linked device and bridges messages to your Claude Code session.

## Install

```sh
# 1. Add this marketplace
/plugin marketplace add Rich627/whatsapp-claude-plugin

# 2. Install the plugin
/plugin install whatsapp@whatsapp-claude-plugin

# 3. Configure your phone number (country code + number, no +)
/whatsapp:configure <phone>

# 4. Launch with channel
claude --channels plugin:whatsapp@whatsapp-claude-plugin
```

On first launch, a pairing code is printed to your terminal. On your phone: WhatsApp > Settings > Linked Devices > Link a Device > **Link with phone number instead** > enter the code.

See [plugins/whatsapp-channel/README.md](./plugins/whatsapp-channel/README.md) for full documentation.
