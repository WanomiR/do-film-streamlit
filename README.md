# DoFilm Streamlit
DoFilm prototype build with Streamlit.

## Application setup
1. Create a Python virtual environment.
    ```bash
   python3.10 -m venv venv && cd venv
   source venv/bin/activate
    ```
2. Install required packages.
    ```bash
   pip install -r requirements.txt
   ```
3. Clone [rawpy repo](https://github.com/letmaik/rawpy) and install the package.
    ```bash
   git clone https://github.com/letmaik/rawpy && cd rawpy
   pip install . && cd ..
   ```
4. Launch the app.
    ```bash
   python3.10 DoFilm.py
    ```