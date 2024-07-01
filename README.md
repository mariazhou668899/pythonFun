# Compiling Guide for LoveStorying App

## Downloading the Source Code

1. Download the source code from the `testQuiz` branch: [LoveStoryingFinalTest - testQuiz](https://github.com/mariazhou668899/LoveStoryingFinalTest/tree/testQuiz)

## Setting Up the Development Environment

1. **Install Node.js**: Node.js is required to install dependencies.

2. **Install Expo CLI**: Run the following command to install Expo CLI:

    ```bash
    npm install -g expo-cli
    ```

3. **Navigate to the Source Code Directory**: Change directory to `LoveStoryingFinalTest` where the source code is located.

4. **Install Dependencies**: Run the following command to install all necessary dependencies:

    ```bash
    npx expo install
    ```

5. **Start the Server**: Use the following command to start the server for the simulator:

    ```bash
    npx expo start
    ```

## Testing the App

### Option A: Using Expo Go App (Recommended)

1. Download the Expo Go app on your mobile device.
2. Scan the QR code shown in the terminal window.
3. Test the app on your phone.

### Option B: Using iPhone Simulator (macOS)

1. Press `i` in the terminal window.
2. The app will open in an iPhone simulator (requires XCode).

### Option C: Using Android Simulator

1. Press `a` in the terminal window.
2. The app will open in an Android simulator (requires Android SDK).

### Option D: Using Web Browser

1. Press `w` to open the app in your browser. Note that the formatting is not optimized for the web, but the app will still be functional.

2. Configure routing to the server:
   - Open [localtunnel](http://openaiserver.loca.lt/).
   - Enter the permission code: `50.47.198.95` into the “Tunnel Password”.
   - Click “Click to Submit”.
   - Verify the router is working: open [localtunnel](http://openaiserver.loca.lt/) in your browser again. You should see the message: "OpenAI Proxy Service is running".
   - If you do not see this message, please email Maria Zhou on Canvas.

## Logging In

Once the app is running, you can either create a new account or use the following credentials:

- **User**: `admin@hotmail.com`
- **Password**: `123456`

## Video Demo

Watch a demo of the LoveStorying App to see basic navigation and features, including account creation, story generation, viewing stories, questionnaires, push and pull stories from the database, and viewing stories created by other users in the community.

[Video Demo Link](#) (replace `#` with the actual URL)

