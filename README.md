# Secured Option Chain Dashboard (Streamlit Cloud, Python 3.13 Compatible)

## Setup on Streamlit Cloud
1. Push this project to GitHub.
2. On Streamlit Cloud → Create new app → Connect GitHub repo.
3. Make sure files are at repo root: app.py, requirements.txt, README.md.
4. In Streamlit Cloud → App Settings → Secrets, add:

MASTER_PASSWORD="your_master_password"
API_KEY="your_api_key"
CLIENT_ID="your_client_id"
PASSWORD="your_password"
TOTP="your_totp"

5. Deploy. First build may take 5–10 minutes.

## Notes
- Uses `st.secrets` (no .env needed)
- Python version is forced by Streamlit Cloud (currently 3.13.6)
- Dependencies are pinned to versions compatible with Python 3.13
