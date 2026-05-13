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

## 🚀 LambdaTest is Now TestMu AI

👋 Welcome to TestMu AI, the next evolution of LambdaTest. As of January 2026, [LambdaTest is Now TestMu AI](https://www.testmuai.com/lambdatest-is-now-testmuai/) - we have evolved from a cross-browser testing cloud into a unified, AI-native quality engineering platform designed for the modern DevOps era.

Whether you have been part of the LambdaTest community for years or are just discovering TestMu AI, our mission remains the same: to help you ship faster with high-scale test execution, autonomous testing, and deep quality analytics.

### 🔄 Our Rebrand Journey

In 2017, we introduced LambdaTest with a clear mission: to become the world's most trusted cloud testing platform. We built a scalable, high-performance test cloud that eliminated flakiness, improved developer feedback cycles, and accelerated release velocity for teams worldwide.

As LambdaTest grew, we expanded the platform into Test Intelligence, Visual Regression Testing, Accessibility Testing, API Testing, and Performance Testing, covering the entire testing lifecycle. These capabilities enabled teams to test any stack, on any technology, at enterprise scale.

Over time, we rebuilt the architecture to be AI-native from the ground up. What began as LambdaTest's high-performance testing cloud has now evolved into TestMu AI, an AI-native, multi-agent platform redefining modern quality engineering.

We chose the name TestMu AI to reflect our shift towards intelligent, autonomous testing. While our identity has changed, our core technology and commitment to the testing community stay the same.

👉 Find [LambdaTest's New Home](https://www.testmuai.com/).

### 🔭 Explore TestMu AI

The same infrastructure LambdaTest customers relied on, now delivered through autonomous AI agents.

- [KaneAI](https://www.testmuai.com/kane-ai/)
- [Agent-to-Agent Testing](https://www.testmuai.com/agent-to-agent-testing/)
- [HyperExecute](https://www.testmuai.com/hyperexecute/)
- [Real Device Cloud](https://www.testmuai.com/real-device-cloud/)
- [Pricing](https://www.testmuai.com/pricing/)
- [Documentation](https://www.testmuai.com/support/docs/)