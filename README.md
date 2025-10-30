# StockScout-AI

Finding the correct products for customers in retail is difficult.  
StockScout solves this.  
We are an AI solution that matches the best product to the customer. 

## Summary 
StockScout is an AI assistant for sales associates that delivers instant in-store similar product suggestions, matching the best product to the customer.


## Background
### Desirability:
Today's shoppers expect a seamless in-store experience and have less tolerance for shortfalls; when the right product isn’t immediately findable, they walk. Associates need a fast way to connect the best product to the customer; StockScout makes that instant. 

Zero consumers are a rising and global phenomenon, who are characterized by having zero loyalty, zero midrange (either scrimp or splurge), valuing sustainability and being omnichannel consumers (Das et al.). Most notably, zero consumers expect in-store retailers to have the same convenience as online  shopping (Das et al.). Shoppers expect to find and purchase products anywhere at anytime, however 71% are leaving without items they came to buy (Zebra Technologies Corp). According to a Salesforce's 2024 Connected Customer study, data from over 16,500 consumers and business buyers shows that poor customer service is the second top reason why customers stop buying (Salesforce). Retailers are suffering a $162.7 billion in lost margin each year in America from in-store inefficiencies (Simbe Robotics). As a result, 81 percent of retail associates shared that their company would benefit from more advanced inventory management tools (Tapscott). In particular, 61 percent of associates said artificial intelligence will help them create a better customer experience (Zebra Technologies Corp). 

Considered holistically, the data shows that zero consumers are on the rise, and their new shopping behaviors have little patience for inefficiencies. With low levels of loyalty, attracting and retaining customers is becoming more difficult. Brilliant customer service is a necessity in retaining current customers, increasing acquired customers and decreasing customer attrition. Associates are in need of a tool that can help them meet the expectations of today's shopper, and the implementation of AI is increasingly important for retailers who want to stay ahead of the competition. StockScout is an AI solution that allows customers to find the correct in-store product efficiently. 

### How StockScout helps:
1) **Decreases wait time:** Optimises lookup and retrieval.
2) **Mitigates retrieval error rate:** Correct item/size/colour pulled; second runs rarely required.
3) **Streamlines Operations:** Minimises FOH and BOH back-and-forth.

## How is it used?
A customer can’t find a product on the floor, so an associate opens StockScout AI on their handheld. The associate starts either a **Specific Product Request** (scan barcode or enter style code) or a **Specific Trait Request** (describe what the customer wants). A **Hard Constraints** step then sets guardrails—**division, gender, size (+ allowed deviation), and category**. StockScout returns the **top 5 in-store matches** ranked by similarity. The associate reviews results with the customer, requests items from BOH if needed, or refines the search to improve the fit.

### Flow 
<img width="9892" height="2966" alt="Untitled diagram-2025-10-29-200509" src="https://github.com/user-attachments/assets/245e915c-5b5a-428a-b72c-2bb5488bfdc6" />


### Rough Mockup 
<img src="https://github.com/user-attachments/assets/01336a46-fada-454f-985d-810a9ce505e1" width="30%" height="30%"/>
<img src="https://github.com/user-attachments/assets/8a70a791-7208-44e3-a880-72eae95cd862" width="30%" height="30%"/>



## Data sources and AI methods

### Inventory System Data: 
Product Name  
Brand 
SKU  
style code  
UPC/EAN   
Amount of stock  
Bin  
colour  
Size  
Division (e.g. apparel, footwear)  
Category (e.g. training, running, basketball)  
RRP: €149.99 → Current: €129.99 (Markdown 1)  
Gender  

### Potential AI Methods:
* **k-Nearest Neighbors (k-NN)** 
* **Bag-of-words / TF-IDF**
* **Logistic regression**
* **Simple optimization / hill climbing**

## What next?
I am in need of a programmer / data scientist to help this become reality, please contact me if interested. 

## Bibiliography 

Das, Resil, et al. ““Zero Consumers”: What They Want and Why It Matters | McKinsey.” Www.mckinsey.com, 18 Oct. 2023, www.mckinsey.com/industries/retail/our-insights/zero-consumers-what-they-want-and-why-it-matters.  
  
Salesforce. A Letter from Salesforce’s Chief Ethical & Humane Use Officer. 2024.  
  
Simbe Robotics. “Retailers Race to Adopt Store Intelligence as Inefficiencies Swell to $162.7B and Threaten Margins.” GlobeNewswire News Room, Simbe Robotics, 17 June 2025, www.globenewswire.com/news-release/2025/06/17/3100709/0/en/Retailers-Race-to-Adopt-Store-Intelligence-as-Inefficiencies-Swell-to-162-7B-and-Threaten-Margins.html. Accessed 23 Oct. 2025.  
  
Tapscott, Kevin. “Out-of-Stocks: A Hidden Crisis in Retail | Zebra.” Zebra Technologies, 13 Aug. 2024, www.zebra.com/us/en/blog/posts/2024/out-of-stocks-hidden-crisis-retail.html.  
  
Zebra Technologies Corp. “Zebra 14th Annual Global Shopper Study.” 3 Nov. 2021.  

## Acknowledgements 
* Created as part of the Building AI course from the University of Helsinki and Reaktor


