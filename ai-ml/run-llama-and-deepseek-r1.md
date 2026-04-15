## Run LLAMA and Deepseek R1 Model Locally Leveraging Ollama – Hands-On
### Running LLAMA and Deepseek R1 Model Locally Using Ollama on a Dell Laptop – Hands-On Guide

This guide is designed for teaching students how to run the LLAMA and Deepseek R1 models locally on a Dell laptop using Ollama. Follow these detailed steps for a successful hands-on experience.

#### 1. **Prerequisites**

Before you begin, ensure that the Dell laptop meets the following requirements:

- **Operating System**: Windows 10 or later (or WSL for Windows users), or Linux-based OS.
- **Processor**: Intel i5 or better for decent performance.
- **RAM**: At least 16 GB recommended.
- **Storage**: Sufficient SSD space for model files (minimum of 10 GB free).
- **Python**: Version 3.8 or later installed.

#### 2. **Installing Ollama**

Ollama is necessary for running models efficiently. On a Windows machine, you can use WSL or Install Docker. Here’s how to set it up:

##### **Option 1: Using WSL (Windows Subsystem for Linux)**

1. **Enable WSL**:
   - Open PowerShell as Administrator and run:

     ```bash
     wsl --install
     ```

   - This command will install WSL. Restart your laptop if prompted.

2. **Install a Linux distribution** (like Ubuntu) from the Microsoft Store.

3. **Open your WSL terminal** (e.g., Ubuntu) and update your package list:

   ```bash
   sudo apt update
   ```

4. **Install necessary packages** (if not already installed):

   ```bash
   sudo apt install curl
   ```

5. **Install Ollama** by running:

   ```bash
   curl -sSfL https://ollama.com/download.sh | sh
   ```

6. **Verify the installation**:

   ```bash
   ollama --version
   ```

##### **Option 2: Using Docker Directly (without WSL)**

1. **Install Docker Desktop**:
   - Go to the [Docker website](https://www.docker.com/products/docker-desktop) and follow the instructions to download and install Docker Desktop for Windows.
   - Ensure Docker is running after installation.

2. **Run the Ollama image**:

   ```bash
   docker pull ollama/ollama
   ```

#### 3. **Downloading the Models**

Next, you’ll need to download the LLAMA and Deepseek R1 models from within your terminal.

1. **To download LLAMA**:

   ```bash
   ollama pull LLAMA
   ```

2. **To download the Deepseek R1 model**:

   ```bash
   ollama pull Deepseek-R1
   ```

#### 4. **Running the Models**

Once the models are downloaded, you can run them directly from your terminal.

1. **Launching LLAMA**:

   ```bash
   ollama run LLAMA
   ```

   You’ll enter a console where you can start typing prompts and interacting with the LLAMA model.

2. **Launching Deepseek R1**:

   ```bash
   ollama run Deepseek-R1
   ```

   Just like with LLAMA, this will start Deepseek R1, allowing for interaction.

#### 5. **Interacting with the Models**

Encourage students to type in various queries to see how the models respond. Here are some suggestions:

- Generate creative stories or responses.
- Ask factual questions to gauge the model’s knowledge.
- Experiment with different prompt styles to observe varying outputs.

#### 6. **Experimenting and Fine-Tuning**

Encourage students to experiment further with the models. Here are some ways:

- Adjust parameters if applicable (like temperature settings for randomness).
- Compare outputs from both models for the same input.
- Discuss why the models might give different outputs.

#### 7. **Conclusion**

Running LLAMA and Deepseek R1 models on a Dell laptop using Ollama offers an excellent opportunity to teach hands-on AI concepts. 

- Encourage your students to work together to solve issues and share findings.
- Foster an environment where they can ask questions and explore the capabilities of these models.

### Additional Tips

- Make sure students understand the ethical considerations of using AI models.
- Remind them to save their work and document their experiments for future reference.

Happy teaching, and enjoy the exploration of AI with your students!
