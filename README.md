# ai-study-buddy
My python study assistant project
import 

st.title("AI Study Buddy")

st.write("Welcome to my Study Assistant!")
st.write("Ask a question and get an answer.")

subject = st.selectbox(
    "Choose Subject",
    ["Science", "English", "Computer", "General Knowledge"]
)

question = st.text_input("Enter your question")

if st.button("Submit"):

    q = question.lower()

    if q == "":
        st.write("Please enter a question.")

    elif "photosynthesis" in q:
        st.write("Plants make their food by using sunlight. This process is called photosynthesis.")

    elif "gravity" in q:
        st.write("Gravity is the force which pulls objects towards the Earth.")

    elif "water" in q:
        st.write("Water is necessary for all living things. Its chemical formula is H2O.")

    elif "computer" in q:
        st.write("A computer is an electronic device which processes data.")

    elif "ai" in q:
        st.write("AI stands for Artificial Intelligence. It helps machines perform smart tasks.")

    else:
        st.write("Sorry, I don't know this answer.")

st.write("Thank you for using AI Study Buddy!")
st.write("Created by Sohan")
