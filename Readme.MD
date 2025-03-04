pip install langchain_google_genai
pip install --upgrade langchain-community langchain-openai sqlalchemy
pip install pymysql

**Check Library versions**

pip show 'library-name'

Eg: 

**pip show langchain**

To update library

pip install --upgrade langchain

**Start streamlit in normal mode**

Streamlit run Project.py

**Start streamlit in Debug Mode**

streamlit run app.py --logger.level=debug

**To install libraries from requirements.txt file**

pip install -r requirements.txt
