import streamlit as st

# App Config
st.set_page_config(page_title="TN Eco Revise", page_icon="🌿", layout="centered")

st.title("🌿 TN Environment: Prelims Revise")
st.caption("High-Yield Review: East Coast vs. West Border Ecosystems")

# Use tabs for clean mobile navigation
tab1, tab2, tab3 = st.tabs(["🌊 East Coast (BoB)", "⛰️ West Border (Arabian Sea)", "📝 Quick Quiz"])

with tab1:
    st.header("Bay of Bengal Influence")
    st.subheader("Pichavaram & Muthupet Mangroves")
    st.write("Major carbon sinks (Blue Carbon) acting as cyclone shields.")
    st.info("**Key Flora:** *Rhizophora* (stilt roots) & *Avicennia* (pneumatophores).")
    
    st.subheader("Gulf of Mannar Biosphere Reserve")
    st.write("India's first Marine Biosphere Reserve (Rameswaram to Kanyakumari).")
    st.warning("**Flagship Fauna:** Dugong (Sea Cow) - Vulnerable, Schedule I, entirely dependent on sea-grass.")
    
    st.subheader("Coromandel Coast (TDEF)")
    st.write("**Tropical Dry Evergreen Forests**: Highly unique, restricted to narrow coastal strips. Sustained primarily by the Northeast Monsoon (NEM).")

with tab2:
    st.header("Arabian Sea Influence")
    st.subheader("The Orographic Engine")
    st.write("The Western Ghats catch the Southwest Monsoon (SWM), creating a massive rain shadow effect.")
    
    st.subheader("Agasthyamalai Biosphere Reserve")
    st.write("Straddles TN and Kerala. Transitions from Wet Evergreen (windward) to Dry Deciduous (leeward/TN side).")
    
    st.success("**UPSC Key Species:** Nilgiri Tahr (Endangered), Malabar Spiny Dormouse.")
    st.info("**Biodiversity Act Example:** Arogyapacha medicinal plant utilized by the local Kani tribe (Access and Benefit Sharing).")

with tab3:
    st.header("Test Your Knowledge")
    
    q1 = st.radio(
        "1. Which marine mammal is the flagship species of the Gulf of Mannar?",
        ["Irrawaddy Dolphin", "Dugong (Sea Cow)", "Sperm Whale", "Olive Ridley Turtle"],
        index=None
    )
    if q1 == "Dugong (Sea Cow)":
        st.success("Correct! It's a strictly herbivorous marine mammal.")
    elif q1:
        st.error("Incorrect. Review the Bay of Bengal tab!")

    q2 = st.radio(
        "2. Which monsoon is primarily responsible for sustaining the Tropical Dry Evergreen Forests?",
        ["Southwest Monsoon", "Northeast Monsoon", "Pre-monsoon showers", "Western Disturbances"],
        index=None
    )
    if q2 == "Northeast Monsoon":
        st.success("Spot on! The Coromandel coast relies heavily on the NEM.")
    elif q2:
        st.error("Incorrect. Think about the East Coast's primary rain source.")
