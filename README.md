This project uses [CommunicationMod](https://github.com/ForgottenArbiter/CommunicationMod)
to interface with Slay The Spire.

# Requirements
- Slay the Spire
- [CommunicationMod](https://github.com/ForgottenArbiter/CommunicationMod)
- ModTheSpire (https://github.com/kiooeht/ModTheSpire)
- BaseMod (https://github.com/daviscook477/BaseMod)

# Instruction

First, let Communication Mod create a config file by running ModTheSpire with CommunicationMod enabled.
Edit the CommunicationMod config file to include the following line. (see [here](https://github.com/kiooeht/ModTheSpire/wiki/SpireConfig) for the config location)

```
command=(cd ~/Projects.git/decode-the-spire && make client)
```