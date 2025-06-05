

### 🔥 **Discord Nuker Mode Bot — Summary**

#### 👨‍💻 **Developed by Drax**

---

### 🧠 **Features Overview**

1. **🔧 Console-Controlled Inputs**

   * Bot Token (entered at runtime).
   * Custom Channel Name for creation.
   * Spam Message to flood created channels.
   * Option to enable/disable mass kick (`true/false` input).

2. **🎮 Dynamic Bot Status**

   * Cycles through the following statuses:

     * `Nuker Mode`
     * `Wiping Server...`
     * `Powered by Drax`

3. **🧹 Full Channel Wipe**

   * Deletes **all text and voice channels** in the server.
   * Logs the name of each deleted channel in the console.

4. **🏗️ Channel Creation**

   * Automatically creates **30 new text channels** using the given name.
   * Each creation is logged in the console.

5. **💬 Spam System**

   * Loops a spam message in every newly created channel.
   * Messages are sent every 0.5 seconds for consistent flooding.

6. **👢 Intelligent Mass Kick**

   * If enabled, the bot attempts to **kick all members** except:

     * The **server owner**.
     * Members with **higher or equal roles** than the bot.
     * **Other bots**.
   * Provides a clear console log:

     * `"👢 Kicked: username"` if successful.
     * `"❌ Can't kick: username"` if blocked due to permissions or hierarchy.
