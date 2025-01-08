
# Caddy Web UI

Caddy Web UI is a user-friendly interface for managing Caddy server configurations. The application allows users to create, edit, and delete site configurations, manage files associated with these sites, and reload the Caddy server directly from the web interface.

## Features
- Add, edit, and delete site configurations.
- File management with uploads, deletions, and ZIP extraction.
- Reload Caddy server configurations.
- User authentication and session management.

## Prerequisites
- Python 3.8 or higher
- Flask framework
- Caddy server installed on the host system

  ![image](https://github.com/user-attachments/assets/2000a9c2-d4c0-4d57-8bc1-ba82e01fee1e)

  ![image](https://github.com/user-attachments/assets/208f9038-8885-4728-b7de-2ff8f02382ab)

  ![image](https://github.com/user-attachments/assets/c0657598-f0b5-48a2-8596-030e389e1fde)

  ![image](https://github.com/user-attachments/assets/6e128c74-9423-456f-9671-bd72397b2cd4)

  ![image](https://github.com/user-attachments/assets/4ebfb5ae-6f2d-487e-8000-5c2a04b00f25)




## Installation

1. Clone this repository:
   ```bash
   https://github.com/ATurner96/Caddy-Web-UI.git
   cd caddy-web-ui
   ```

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure the application by editing `app/config/config.json`:
   - Update the `base_dir`, `caddyfile`, `port`, and `secret_key` as needed.

4. Run the application:
   ```bash
   python run.py
   ```

5. Open your browser and navigate to `http://localhost:5154` (or the configured port).

## Directory Structure
```
.
├── app/
│   ├── config/
│   │   └── config.json
│   ├── static/
│   │   └── styles.css
│   ├── templates/
│   │   ├── login.html
│   │   ├── setup.html
│   │   └── index.html
│   ├── routes.py
│   └── utils.py
├── run.py
├── requirements.txt
└── README.md
```

## Development

To enable debugging, set `debug=True` in `run.py`.

## License
This project is licensed under the GNU General Public License v3.0.

For more details, see the [LICENSE.txt](LICENSE.txt) file or visit the [GNU website](https://www.gnu.org/licenses/gpl-3.0.html).
