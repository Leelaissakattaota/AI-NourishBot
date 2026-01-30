# 🥗 AI NutriCoach (Powered by Multi-Agent System)

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![Gradio](https://img.shields.io/badge/UI-Gradio-orange.svg)
![CrewAI](https://img.shields.io/badge/Framework-CrewAI-red.svg)
![WatsonX](https://img.shields.io/badge/AI-IBM%20WatsonX-darkblue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

[cite_start]**AI NutriCoach** is an intelligent personal health companion that goes beyond simple food tracking[cite: 6, 7]. [cite_start]By leveraging state-of-the-art vision models and a Multi-Agent System (MAS), it identifies ingredients from images, applies dietary filters, and provides actionable nutritional insights or recipe suggestions[cite: 10, 11, 12].

---

## 🌟 Key Features

* [cite_start]**🔍 Multimodal Food Detection:** Utilizes Meta Llama 3.2 90B Vision Instruct to accurately recognize ingredients from food images[cite: 8, 304].
* [cite_start]**🥗 Smart Dietary Filtering:** Filters ingredients based on user-defined restrictions such as Vegan, Keto, or Gluten-free[cite: 44, 46, 47].
* [cite_start]**📊 Comprehensive Nutrient Analysis:** Provides detailed breakdowns of calories, macronutrients (protein, carbs, fats), and micronutrients[cite: 39, 40, 41, 42].
* [cite_start]**👨‍🍳 AI Chef (Recipe Generation):** Creates healthy, easy-to-prepare recipes using identified and compliant ingredients[cite: 43, 45].
* [cite_start]**🤖 Multi-Agent Orchestration:** Powered by CrewAI to coordinate specialized agents for complex decision-making[cite: 10, 498].

---

## 🧠 Architecture & Agents

[cite_start]The project employs a structured **Multi-Agent System** where each agent has a specific role and backstory to ensure high-quality outputs[cite: 11, 528, 530].

| Agent | Role | [cite_start]Responsibility [cite: 530] |
| :--- | :--- | :--- |
| **Vision Specialist** | Ingredient Detection | Identifies food items from uploaded images. |
| **Nutritionist Agent** | Dietary Filtering | Ensures ingredients comply with dietary needs. |
| **Analysis Specialist**| Nutrient Analysis | Calculates calories and nutritional value. |
| **AI Chef** | Recipe Suggestion | Generates creative recipes from filtered lists. |



---

## 🛠️ Tech Stack

* [cite_start]**Language:** Python 3.11 [cite: 146]
* [cite_start]**Orchestration:** CrewAI (Agentic Framework) [cite: 155, 497]
* [cite_start]**AI Models:** Llama-3.2-90B-Vision-Instruct, Granite-3.1-8B [cite: 85, 127, 362]
* [cite_start]**Web Interface:** Gradio [cite: 13, 155]
* [cite_start]**Backend Tools:** LangChain, IBM WatsonX AI SDK, Pydantic [cite: 156, 157]

---

## 💻 Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/Leelaissakattaota/AI-NourishBot.git](https://github.com/Leelaissakattaota/AI-NourishBot.git)
cd AI-NourishBot


2. **Create and activate a virtual environment**:

  ```bash

  python -m venv venv

  source venv/bin/activate  # On Windows: venv\Scripts\activate

  ```

3. **Install the required dependencies:**

  ```bash

  pip install -r requirements.txt

  ```

4. **Create a .env file in the root directory with the following keys**:

   ```bash

    WATSONX_API_KEY=your_watsonx_api_key

    WATSONX_URL=your_watsonx_url

    WATSONX_PROJECT_ID=your_watsonx_project_id

   ```

## Usage

### Run the Application



You can run the application using the following commands:



1. For recipe suggestions



```bash

python main.py <image_path> <dietary_restrictions> recipe

```



Example:



```bash

python main.py food.jpg vegan recipe

```



2. For food analysis



```bash

python main.py <image_path> analysis

```



Example:



```bash

python main.py food.jpg analysis

```



3. For training (future functionality - TODO)



```bash

python main.py train <n_iterations> <output_filename> <image_path> <dietary_restrictions> <workflow_type>

```



## File Structure



```

Smart-Nutritional-App-Crew/

│

├── config/

│   ├── agents.yaml               # Configuration for agents

│   └── tasks.yaml                # Configuration for tasks

│

├── src/

│   ├── crew.py                   # Crew definitions (agents, tasks, workflows)

│   ├── tools.py                  # Tool definitions for ingredient detection, filtering, etc.

│   └── main.py                   # Main script for running the application

│

├── requirements.txt              # Python dependencies

└── README.md                     # Project documentation

```



## Contributing



Contributions are welcome! If you have suggestions for improvements or new features, please create a pull request or open an issue.



## License



This project is licensed under the MIT License. See the LICENSE file for details.



## Contact



For any questions or support, please contact [Hailey Thao Quach](mailto:hailey@haileyq.com).

can you give me this mrkdown as colour full and profissional way
