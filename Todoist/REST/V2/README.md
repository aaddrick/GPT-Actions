# Todoist RESTv2 OpenAPI Documentation

This repository contains the OpenAPI 3.1.0 specification for the Todoist REST API version 2.
The specification is currently version 1.0.0 as of 2023-11-16.
It has been built with intent to use with ChatGPT 4's Action system, but there's nothing in there specific to OpenAI. The spec should be broadly applicable.

## View API in Swagger Editor

You can view and interact with the API specification using the Swagger Editor. Click the following link to load the specification:

[View API in Swagger Editor](https://editor-next.swagger.io/?url=https://raw.githubusercontent.com/aaddrick/GPT-Actions/main/Todoist/REST/V2/todoist_rest_v2_openapi-3.1.0.yml)

## Implementation

### Todoist

The Todoist REST API allows for basic interaction with Todoist, enabling the creation, update, and management of **Projects**, **Sections**, **Tasks**, **Comments**, and **Labels** . Authentication is performed via API token and not OAuth2.

### OpenAI

Integrating OpenAI with the Todoist API can enhance task management through AI-driven insights and automation. Here are some suggestions for implementation:

- **Natural Language Processing**: Use OpenAI's language models to interpret and categorize tasks or generate task descriptions.
- **Automation**: Implement AI-driven task sorting, prioritization, and recommendation systems.
- **Data Analysis**: Leverage OpenAI for analyzing task patterns, productivity trends, and user behavior.

## Getting Started

To start using this API, follow these steps:

1. Follow the instruction at [Find your API token (todoist.com)](https://todoist.com/help/articles/find-your-api-token-Jpzx9IIlB) and retrieve your API token
2. Browse to [ChatGPTs Discovery (openai.com)](https://chat.openai.com/gpts/discovery) 
3. Select **Create a GPT**

![Create a GPT](https://github.com/aaddrick/GPT-Actions/blob/main/Todoist/REST/V2/images/Create_a_GPT.png?raw=true)

5. Switch from the **Create** tab to the **Configure** tab

![Create / Configure](https://github.com/aaddrick/GPT-Actions/blob/main/Todoist/REST/V2/images/Create-Configure.png?raw=true)

6. At the bottom left, in the **Actions** section, click the **Create new action** button

![Create a new action](https://github.com/aaddrick/GPT-Actions/blob/main/Todoist/REST/V2/images/Create_new_action.png?raw=true)

7. Select **Import from URL** at the top right of the Schema text box.

![Import from URL](https://github.com/aaddrick/GPT-Actions/blob/main/Todoist/REST/V2/images/Import_from_url.png?raw=true)

8. Copy/Paste the following:
```
https://raw.githubusercontent.com/aaddrick/GPT-Actions/main/Todoist/REST/V2/todoist_rest_v2_openapi-3.1.0.yml
```
8. Select **Import** and wait a few seconds while the YAML loads and the parser determines the available actions.

![Import](https://github.com/aaddrick/GPT-Actions/blob/main/Todoist/REST/V2/images/import.png?raw=true)

9. Scroll all the way down and hit the **gear icon** on the right in the **Authentication** section.

![Gear Icon](https://github.com/aaddrick/GPT-Actions/blob/main/Todoist/REST/V2/images/Authentication.png?raw=true)

10. Select **Authentication Type: API Key**, paste the **API Token** you received from step 1, and select **Auth Type: Bearer** before pressing the **Save** button.

![API Key Settings](https://github.com/aaddrick/GPT-Actions/blob/main/Todoist/REST/V2/images/apikey.png?raw=true)

11. Scroll all the way up and press the **<** symbol next to **Add Actions**, not the one next to **New GPT -Draft**.

You can now begin testing on the **Preview** pane on the right, or continue configuring your GPT by switching back to to the **Create** tab.


## Contributing

Contributions to this API documentation are welcome. Please feel free to submit pull requests or raise issues for any improvements or suggestions.



## Disclaimer

Please note that this documentation and the associated GitHub repository are independently created and maintained. **I am not affiliated, associated, authorized, endorsed by, or in any way officially connected with Todoist, Doist Inc., OpenAI, or any of their subsidiaries or affiliates.**

The official Todoist website can be found at [https://todoist.com](https://todoist.com), and information about OpenAI is available at [https://openai.com](https://openai.com). The names Todoist and OpenAI as well as related names, marks, emblems, and images are registered trademarks of their respective owners.

This project is a personal endeavor to contribute to the developer community by providing an OpenAPI specification for Todoist’s REST API version 2. It is intended for educational and informational purposes only.

