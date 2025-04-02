# ⚙️ Missions Configuration

### Accessing Mission Configuration

1. Navigate to the 'Engage' section and select 'Achievements'.
2. Click on 'Missions' to begin configuring your mission groups.

***

### **Information**

* **Mission Icon**: Upload an icon that represents the mission visually.
* **Display Name**: Provide a name for the mission that players will see.
* **Mission ID**: Assign a unique identifier to ensure no duplication.
* **Description**: Offer a brief description of the mission's objectives and significance.

***

### **Configure**

* **Choose Type**: Select the mission cycle type from daily, weekly, or static options.
* **Number of Missions per Cycle**: Define how many missions will appear in each cycle.
* **Grant Reward**: Choose the reward distribution method—either server-side (automatically bestowed upon completion) or on claim (requires player action).

***

### **Tasks**

* **Add Tasks**: Incorporate tasks into the mission by selecting from existing tasks or creating new ones. This step is crucial for building out the content of your mission.
  * **Select from Existing**: Choose tasks previously created, with an option to modify the task ID for mission specificity.
  * **Create New Task**: Craft new tasks by detailing task information, configuring task logic, and setting rewards similar to the standalone task configuration process.

See Task Configuration to learn how tasks are configured using events.

{% content-ref url="../tasks/task-configuration.md" %}
[task-configuration.md](../tasks/task-configuration.md)
{% endcontent-ref %}

***

### Mission Group Rewards

* Designate rewards for completing the entire mission group within the cycle. Like task rewards, you can select items, currencies, bundles, progression markers, or configure third-party rewards. Determine the quantity each player will receive upon mission group completion.

***

### Access and Eligibility

* **Lock by Level**: Set access conditions based on player levels.
* **Choose Progression System**: Link mission group availability to a specific progression system, selecting it from the dropdown.
* **Level System Level**: Specify the level within the chosen progression system that unlocks the mission group.

***

### Custom Data

* **Tags**: Utilize tags for better organization and searchability.
* **Meta Data**: Input additional details as key-value pairs for deeper mission configuration.
