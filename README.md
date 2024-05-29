# AI_Final_Project

Topic Selected - NLP
This project likely is fitting "Max" requirement - which covers usable end-2end system with an ML Model (that was not covered in class)

Model training:
https://colab.research.google.com/drive/1-swZ2MeHqbjly16hT0CsD8x_sxHWYBPS?usp=sharing

Backend
Built with flask. 
https://github.com/gcilinskas/ai_fake_review_detector

Usage example:
curl --location 'https://api.reviewpolice.com/predict' \
--header 'Content-Type: application/json' \
--data '{
    "text": "Great product!"
}'

Frontend
This is chrome extension. To load it you can just drag extension project folder to your extensions
https://medium.com/@aabroo.jalil/how-to-test-a-chrome-extension-locally-step-by-step-guide-852e4622d4c7

Whether review is fake or not, it will be displayed in chrome on amazon page, if extension is enabled.
To test it once extension is loaded these pages can be used as example:
from product page: https://www.amazon.com/dp/B01H6GUCCQ 
or review page: https://www.amazon.com/product-reviews/B01H6GUCCQ


