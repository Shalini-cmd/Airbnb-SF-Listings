# Airbnb-SF-Listings
Analyzed SF listings data to understand the AirBNB pricing <br>
Airbnb is one of the classic examples of product disruption. Founded in 2008, it became the first online platform that allows hosts to put up their apartments and homes on the site to be rented by guests. Today, with more than 2 million listings in over 191 countries, Airbnb’s biggest challenge has been to help the hosts increase the number of bookings that will, in turn, help the company thrive in the long run. In this report, we focused on two key items that most consumers consider when booking a listing – price, and ratings, the factors that affect each one separately and jointly. To this end, we built two separate models for price and ratings respectively and found that prices are usually affected by the amenities and neighborhood while ratings are primarily affected by host responsiveness. Upon further analysis, it was discovered that being a super host drives out higher ratings for users that allows them to leverage and charge higher nightly rates. With that in mind, we have come up with the following recommendations:<br>
- Property-centered improvements. Factors affecting price are centered on property attributes. Thus, it is recommended that the company educate hosts on property acquisition, improvement as well as maintenance.
- Host-User relationship improvements. Key factors impacting ratings are centered on how established communication is between a host and a user. Thus, knowledge about best practices in the hospitality industry may be imparted to hosts.
- Super host business model. Super host is a factor that’s overlapping for both price and ratings. To this end, recommendations above helps hosts improve as super hosts.
Further analysis revealed that conversion of hosts to super hosts provide a monthly increase in revenue of 2%. Thus it may be favorable to highlight this incentive to the hosts.

### Problem Formulation
Airbnb caters to two types of customers - guests and hosts. For guests, the ease of booking and how fairly the listings are priced plays a significant role in driving their loyalty with Airbnb. Similarly, how often a host listing is booked and rental fee affects the association of a host with Airbnb. Hence, we realized listing price and ratings are features that affect both hosts and guests in one way or another. In order to stay on top, Airbnb has to frame strategies around these to stay ahead in their game compared to its competitors.<br>

We also found that listings on the higher end of the price spectrum tend to have higher ratings on average. Hence, in order to better understand the effect of price and ratings on value addition for Airbnb, we took the following steps:<br>
- Built a linear regression model to understand which factors significantly affect pricing.
- Built a random forest classifier model to discern those aspects of a listing that affect the ratings received on the portal.<br>
In an ideal setting, price and ratings would be independent of each other. However, in real life, when a guest is providing reviews, they would look at it from the perspective of whether the price was justified or not. Even while booking their stay, guests check the reviews and judge whether the price would be worth the amenities.
<br>
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



