import streamlit as st

st.set_page_config(page_title="Pour mon Paul d'amour❤️")

st.title("Coucou, oui c'est encore ta copine hyper reloue...mais je voulais te dire un truc <3")
st.write("en attendant que tu aies ton joli site pour la St-Valentin et comme je sais que ce soir tu es pas en forme, je voulais te rappeler à quel point tu es précieux à mes yeux et à quel point je t'aime de tout mon coeur. ALors s'il te plait, clique sur le bouton en dessous <3")
# Liste des messages
messages = [
    "Coucou Paul ",
    "Tout d'abord, tu me manques",
    "Ensuite, ",
    "Merci pour la super journée que l'on a passé ensemble ",
    "je passe toujours des moments merveilleux avec toi",
    "tu es mon coeur,",
    "mon amour,",
    "ma lumière,",
    "mon soleil",
    "et je suis tellement amoureuse de toi",
    "je suis tellement fière d'être ta copine",
    "mais mon coeur que j'aime,",
    "ne te laisse jamais faire",
    "continue à faire les choses qui te font sentir vivant,",
    "les choses qui te font du bien",
    "les choses qui te font sentir toi-même",
    "tu vas clutch ce semestre avec de bons objectifs", 
    "et tout ira mieux", 
    "je te fais tellement confiance",
    "en attendant, je suis toujours à tes côtés ",
    "pour t'épauler",
    "te faire des bisous",
    "des calins",
    "et le plus important : ",
    "t'emmerder <3",
    "Bref je t'aime d'amour,", 
    "j'ai hate d'être avec toi", 
    "et psssssttttt", 
    "j'ai envie de te manger tellement t'es beau grrrr",
    "bisouuuuuuuuuuussss"


]

# Initialisation du compteur
if "index" not in st.session_state:
    st.session_state.index = 0

# Bouton
if st.button("Clique ici 💕"):
    if st.session_state.index < len(messages):
        st.session_state.index += 1

# Affichage des messages
for i in range(st.session_state.index):
    st.write(messages[i])
