# SmartUI Storybook Sample — TestMu AI (Formerly LambdaTest)

## Installation

1. Clone this repository
    ```
    git clone https://github.com/LambdaTest/smartui-storybook-sample
    ```

2. Change directory to the downloaded git repo and install packages
    ```
    npm install
    ```

3. Start Storybook 
    ```
    npm run storybook 
    ```

## Running SmartUI storybook tests on a Docker container.

1. Clone this repository
    ```
    git clone https://github.com/LambdaTest/smartui-storybook-sample
    ```
2. Navigate to project directory
    ```
    cd smartui-storybook-sample
    ```
3. Create SmartUI Config JSON
    ```
    smartui config create .smartui.json
    ```
4. Create a docker Image
    ```
    docker build -t <image_name> .
    ```
5. Run a Docker container and test in it
    ```
    docker run -e PROJECT_TOKEN="your_project_token" <image_name>
    ```

## 🚀 [LambdaTest is Now TestMu AI](https://www.testmuai.com/lambdatest-is-now-testmuai/)

👋 Welcome to TestMu AI, the next evolution of LambdaTest. As of January 2026, LambdaTest has officially rebranded to TestMu AI. We have evolved from a cross-browser testing cloud into a unified, AI-native quality engineering platform designed for the modern DevOps era.

Whether you have been part of the LambdaTest community for years or are just discovering TestMu AI, our mission remains the same: to help you ship faster with high-scale test execution, autonomous testing, and deep quality analytics.

**🔄 Our Rebrand Journey**

We chose the name TestMu AI to reflect our shift towards intelligent, autonomous testing. While our identity has changed, our core technology and commitment to the testing community stay the same.

**✨ Specialties**

- 🤖 AI-Native Test Execution (Formerly LambdaTest)
- ⚡ Autonomous Test Automation
- 🌐 Cross-Browser & Mobile Testing
- 📊 Unified Quality Intelligence

👉 Find [LambdaTest's New Home](https://www.testmuai.com/).