# SMART on FHIR Demo

1. Sign Up for a SMART Sandbox Account:
    https://sandbox.smarthealthit.org/#/start

2. Register your local app:
    - Choose the SMART DSTU sandbox
    - Click 'Register New App Manually'
        App Type: Public Client
        App Name: Your App Name
        App Launch URI: http://localhost:8000/launch.html
        App Redirect URIs: http://localhost:8000/
        Allow Offline Access: _
        Patient Scoped App: x
        App Logo (Upload one if you want)
    - Click Save; Take note of the generated app client ID.

3. Clone this repo; CD to the cloned directory and start a local http server:
    ```
    > git clone https://github.com/intertwine/smart-on-fhir-demo.git
    > cd /path/to/the/cloned/repo
    > python -m SimpleHTTPServer 8000 (or use any other http server on your machine)
    ```

4. Edit 'launch.html' to include the new client id generated in Step 2.

5. In the Sandbox, click Launch and select a patient.
