# AirBnB-Listing-Analysis
Melbourne Airbnb Listing Analysis

## Project Background

With Melbourne's popularity as a tourist attraction and for business purposes, many people are coming to Melbourne and looking for a temporary home or a place to stay for the night. Some places have a good location, price, and the type of availability that impact performance. This project throrougly analyze and sysntesizes data to unvocer insights that will help home owner know where to make their listings a success. The purpose of this project is to create an analysis and help the marketing team attract more property owners to become hosts on Airbnb.

Insights and recommendations are provided on the following key areas:

  - **Location Analysis:** Giving potential hosts a clear idea of which locations around Melbourne suburbs are performing well
  - **Listing Analysis:** Help potential hosts know what the most popular housing type is in Melbourne.
  - **Pricing Analysis:** Help host understand pricing through analysis to compare room types and location so they can attract more bookings to their listings.

### Data
Source : https://insideairbnb.com/
Total Data: 76 Collumns and 25382 Rows

### Data Schema

![Image](https://github.com/user-attachments/assets/bedaebfa-795e-4a2f-9140-212d0affa0c1)

## Insights Deep-Dive

### Location Analysis

- **City of Melbourne** has the highest number of listings with **8237**
- **Port Phillip** and **Yarra** also have a large number of listings offering diverse accommodation. Some areas have even fewer listings, likely due to the presence of fewer tourist attractions.
- Regarding guest rating and guest review, with more than 36000 reviews, thanks to its central location and attractions
- There are also some outliers, such as **City of Monash**, which has only 653 listings but over 13,000 reviews with an average rating of **4.6**. This suggests strong guest satisfaction, possibly due to the quality of stays and proximity to universities and business hubs.

![Image](https://github.com/user-attachments/assets/560015e5-3cbf-477d-8ad9-0ca730e60420)![Image](https://github.com/user-attachments/assets/4350d855-101f-4c7d-91e5-876ce7faf6cb)

### Listing Type Analysis

- There are four distinct room types in the listings: **Entire Home/Apartment, Private Room, Shared Room** and **Hotel Room**. Among these, _Entire Home/Apartment _is the most commonly listed followed by _Private Room_. In contrast, _Shared Room_ and _Hotel Room_ represents a much smaller portion of the listings.
- Entire _Home/Apartment_ listings dominate in central and inner-city subrubs such as **Melbourne CBD, Port Phillips,** and **Yarra**. Meanwhile, _Private Rooms_ are more common in outer suburbs, particularly in areas like **Moreland**.
- The **average guest rating** across all room types is **4.7 out of 5**, with exception of _hotel rooms_, which have a slightly lower average rating of **4.5**. These average are calculated across all suburbs included in the dataset.
![Image](https://github.com/user-attachments/assets/a9995bb8-cda8-4ab9-9b08-0573d3243eb2)
![Image](https://github.com/user-attachments/assets/76b86ab4-fce9-421c-bdb6-a8787f3aff31)
![Image](https://github.com/user-attachments/assets/6b88a34b-e79a-4a37-b5b5-3c167c060568)

### Pricing Analysis

- The majority of Airbnb listings across Victoria are priced in the $100–150 and $150–200 ranges, with each category containing approximately 4,000 listings.
- Melbourne CBD maintains high pricing across all room type. Moreland private rooms far exceed its entire home, indicating a possible outliers. Port Phillip seesstrong demand with hotel and entire homes averaging $350. Wyndham's shared rooms are priced above private room suggesting pricing inconsistencies. Additionally, Yarrra Ranges shows high entire home prices aligning wwith deman for retreats or group stays.
- The median price for a private room is around **$100** where most listing fall between **$50 - 150** but there are many outliers where some reach **$800++** this suggest that there are overpricing or luxury offerings.
- The spread in prices across suburbs widens at higher capacities, that indicates location become more significant factor for large accomodation than small ones, which tends to have more consistent pricing across areas.

![Image](https://github.com/user-attachments/assets/2ba62b9e-216d-4e6f-bbec-9f66e8edb051)
![Image](https://github.com/user-attachments/assets/90649ae6-04eb-4500-86f0-73dca4b404d7)
![Image](https://github.com/user-attachments/assets/1e7577ae-50e8-4063-9724-e99197e25c6f)
![Image](https://github.com/user-attachments/assets/5b38ab37-83dc-4a44-8f79-b6aee5b38431)

## Recommendations

### Location Analysis 
1. **Promote listing in underrepresented areas** with a lot of suburbs that have a growth potential, by partnering with local businesses and attractions, it can lead to positioning these locations as an emerging location and increase popularity.
2.  Suburbs with high ratings but fewer listings often indicate hosts who exceed guest expectations. This can include clear communication and thoughtful amenities that lead to better reviews and repeat bookings, even in low-traffic areas.
3.  **Leverage positive guest sentiment in outlier markets**, which have extremely high reviews and strong ratings. By creating targeted campaigns, we can highlight listings as hidden gems to attract new guests.

### Listing Type Analysis
1. **Target promotions around Entire/Home Apartments** in central suburbs like Melbourne CBD, Port Phillip, and Yarra, since these listings dominate and align with traveler preference for privacy and larger spaces.
2. **Consider Private Rooms in outer suburbs** to tap into growing budget-conscious traveler segments or students needing affordable stays.
3. **Invest in Entire Homes/Apartment** in central areas if budget allowed, as some of the listings consistenyly attract high demand and achieve strong guest ratings.
4. **Highlighting competitive advantages of a Private Room** in marketing campagins for outer subrubs like Moreland, positioning them as budget-friendly alternatives then to central accommodations.

### Pricing Analysis
1. **Promote affordability segments** by highlighting well-priced private rooms in $50 - $150 range across marketing materials to attract budget-conscious travellers.
2. **Emphasize premium listings** in marketing campgaigns for high-demand areas like Melbourne CBD and Port Phillip, showcassing them as desirable options for travellers seeking quality and more near to central locations.
3. **Consider property capacity when setting price** for larger accommodations, factor in suburb-specific demand since location impact grows with listing size.
4. Educate hosts on luxury positioning, ensuring listings with unusually high prices that are justified with unique features or amenities to avoid deterring potential guests.
