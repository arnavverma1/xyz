{
  "intents": [
    {
      "tag": "greeting",
      "patterns": ["hello", "hi", "hey", "hlo", "hii", "hiii", "helloo", "heyy", "heyyy"],
      "responses": ["Hello! How can I assist you today?"]
    },
    {
      "tag": "goodbye",
      "patterns": ["bye", "goodbye", "bie", "byee", "byeee"],
      "responses": ["Goodbye! Have a great day."]
    },
    {
      "tag": "name",
      "patterns": ["what should I call you", "what are you called", "name"],
      "responses": ["I am the BloodBot from Metropolis at your service."]
    },
    {
      "tag": "home",
      "patterns": ["home", "house"],
      "responses": ["Yes! You can book an appointment with us, and you can give us your blood sample from the comfort of your home."]
    },
    {
      "tag": "nearest_branch",
      "patterns": ["nearest", "near", "closest", "branch"],
      "responses": ["You can locate our nearest branch by turning your location 'on' in your device and then searching 'Metropolis Lab' on Google."]
    },
    {
      "tag": "booking",
      "patterns": ["book", "booking", "reserve"],
      "responses": ["Unfortunately, at this early stage, I cannot confirm bookings for you. But you can book an appointment with us on our website: https://www.metropolisindia.com/"]
    },
    {
      "tag": "timings",
      "patterns": ["timings", "time", "open"],
      "responses": ["Metropolis labs are open from 7:30 AM to 8:00 PM near you. However, you can contact me on this website at any time :)"]
    },
    {
      "tag": "thanks",
      "patterns": ["thanks", "thank", "ok"],
      "responses": ["Pleased to be helpful."]
    },
    {
      "tag": "contact",
      "patterns": ["call", "phone", "number", "customer", "service"],
      "responses": ["You can reach Metropolis Labs at our customer care number: +91-9814995095 ."]
    },
    {
      "tag": "purpose",
      "patterns": ["use", "used", "purpose"],
      "responses": ["I am here to help you with all your test-related queries."]
    },
    {
      "tag": "information",
      "patterns": ["information", "details", "tell", "more", "about", "detail"],
      "responses": ["Sure, I can provide information about various blood tests. Please specify the test you're interested in."]
    },
    {
      "tag": "unknown",
      "patterns": ["I don't know", "not sure", "confused"],
      "responses": ["I'm sorry, I didn't understand that. Please ask a question about blood tests."]
    },
    {
      "tag": "complete_blood_count",
      "patterns": ["complete blood count", "cbc test", "blood count"],
      "responses": [
        "The complete blood count (CBC) is a blood test used to evaluate your overall health and detect a wide range of disorders.",
        "Price: ₹330",
        "Requirements: Fasting not required"
      ]
    },
    {
      "tag": "lipid_profile",
      "patterns": ["lipid profile test", "cholesterol test", "lipid test"],
      "responses": [
        "The lipid profile is a blood test that measures your cholesterol levels.",
        "Price: ₹800",
        "Requirements: Fasting required for 9-12 hours"
      ]
    },
    {
      "tag": "allergy_panel",
      "patterns": ["allergy panel test", "allergy test", "allergy screening"],
      "responses": [
        "The Allergy Panel test is used to identify specific allergens that may be causing an allergic reaction in the body.",
        "Price: ₹300",
        "Requirements: Fasting required for 8 hours"
      ]
    },
    {
      "tag": "food_intolerance",
      "patterns": ["food intolerance test", "intolerance test", "food sensitivity test"],
      "responses": [
        "The Food Intolerance test helps identify food intolerances or sensitivities that may cause digestive issues or other symptoms.",
        "Price: ₹13500",
        "Requirements: Fasting not required"
      ]
    },
    {
      "tag": "vitamin_d",
      "patterns": ["vitamin d blood test", "vitamin d test", "d3 test"],
      "responses": [
        "The Vitamin D blood test measures the level of vitamin D in the body, which is important for bone health and immune function.",
        "Price: ₹17000",
        "Requirements: Fasting not required"
      ]
    },
    {
      "tag": "thyroid",
      "patterns": ["thyroid test", "tsh test", "thyroid profile"],
      "responses": [
        "The Thyroid test measures the levels of thyroid hormones in the blood, helping to assess thyroid function and detect thyroid disorders.",
        "Price: ₹600",
        "Requirements: Fasting not required"
      ]
    },
    {
      "tag": "glycated_haemoglobin",
      "patterns": ["glycated haemoglobin test", "hba1c test", "blood sugar test"],
      "responses": [
        "The Glycated haemoglobin or HbA1C test provides information about average blood sugar levels over the past 2-3 months, aiding in the management of diabetes.",
        "Price: ₹620",
        "Requirements: Fasting not required"
      ]
    },
    {
      "tag": "thrombophilia_profile",
      "patterns": ["thrombophilia profile test", "blood clot test", "thrombophilia screening"],
      "responses": [
        "The Thrombophilia profile test is used to detect abnormalities in blood clotting that may increase the risk of excessive clot formation.",
        "Price: ₹18500",
        "Requirements: Fasting not required"
      ]
    }
    // Add more intents for other blood tests
    // ...
  ]
}
