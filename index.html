import streamlit as st
import pandas as pd

# --- 1. CONFIGURATION ---
st.set_page_config(page_title='Staff Dev Portal', page_icon='🎓', layout='wide')

# --- 2. DATA SOURCE ---
CONTENT = {
    'OKRs': {
        'title': 'Measure What Matters (OKRs)',
        'desc': 'Focus, Alignment, Tracking, and Stretching.',
        'quiz': {'q': 'What is the main focus of OKRs?', 'a': 'Alignment'}
    },
    'RBA': {
        'title': "Trying Hard Isn't Good Enough (RBA)",
        'desc': 'Results-Based Accountability: Moving from effort to impact.',
        'quiz': {'q': 'RBA shifts focus from effort to what?', 'a': 'Impact'}
    },
    'PMO': {
        'title': 'Leading Successful PMOs',
        'desc': 'Strategic value delivery and agile governance.',
        'quiz': {'q': 'Modern PMOs focus on what kind of delivery?', 'a': 'Value-Driven'}
    }
}

# --- 3. UI STYLING ---
st.markdown('<style>.stProgress > div > div > div > div { background-image: linear-gradient(to right, #4CAF50, #8BC34A); }</style>', unsafe_allow_html=True)

# --- 4. SIDEBAR NAVIGATION ---
st.sidebar.title("🎓 Learning Path")
page = st.sidebar.radio("Navigate", ["Home", "OKRs", "RBA", "PMO", "Knowledge Check"])

# Progress Simulation
if 'xp' not in st.session_state: st.session_state.xp = 0
st.sidebar.markdown("--- ")
st.sidebar.write(f"**Completion Status:** {st.session_state.xp}%")
st.sidebar.progress(st.session_state.xp)

# --- 5. PAGE LOGIC ---
if page == "Home":
    st.title("🚀 Staff Professional Development")
    st.write("Welcome! Use the sidebar to master OKRs, RBA, and PMO strategies.")
    st.image("https://images.unsplash.com/photo-1522202176988-66273c2fd55f?w=800", caption="Continuous Improvement")

elif page in ["OKRs", "RBA", "PMO"]:
    item = CONTENT[page]
    st.title(item['title'])
    st.info(item['desc'])
    st.session_state.xp = min(st.session_state.xp + 25, 75)
    if page == "PMO":
        st.graphviz_chart('digraph { rankdir=LR; Strategy -> Governance -> Value }')
    if page == "RBA":
        st.graphviz_chart('digraph { Data -> Story -> Action }')

elif page == "Knowledge Check":
    st.title("📝 Check Your Knowledge")
    topic = st.selectbox("Choose a topic", ["OKRs", "RBA", "PMO"])
    user_ans = st.text_input(CONTENT[topic]['quiz']['q'])
    if st.button("Submit"):
        if user_ans.lower() == CONTENT[topic]['quiz']['a'].lower():
            st.success("Correct! XP Boosted!")
            st.session_state.xp = 100
            st.balloons()
        else:
            st.error("Try again! Hint: Check the module summary.")
