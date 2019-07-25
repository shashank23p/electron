# Electron Sample
This sample demostrates how to use [Dynamic Web TWAIN SDK](http://www.dynamsoft.com/Products/WebTWAIN_Overview.aspx) in an Electron App.

## How to use the sample

1. Install **Electron**:

    ```bash
    npm install -g electron
    ```

2. Go to [apply for a trial key]() and get a trial key, then put the trial key in the file **index.html* 

    ```javascript
    //Replace A-Valid-Product-Key with your key
    Dynamsoft.WebTwainEnv.ProductKey = "A-Valid-Product-Key";
    ```

3. Run the app:

    ```bash
    electron .
    ```

    or 

    ```bash
    npm start
    ```