# Project: Insights from Failed Orders
1. [ Introduction. ](#intro)
2. [ Data Description. ](#data-desc)
3. [ Exploratory Data Analysis. ](#ex)
4. [ Conclusion. ](#con)

<a name="intro"></a>
## 1. Introduction
Gett, previously known as GetTaxi, is an Israeli-developed technology platform solely focused on 
corporate Ground Transportation Management (GTM). They have an application where clients can order
taxis, and drivers can accept their rides (offers). At the moment, when the client clicks the Order
button in the application, the matching system searches for the most relevant drivers and offers
them the order.In this project, we would like to investigate some matching metrics for orders that
did not completed successfully, i.e., the customer didn't end up getting a car.

<a name="data-desc"></a>
## 2. Data Description

We have two data sets: data_orders and data_offers, both being stored in a CSV format. The data_orders data set contains the following columns:
- `order_datetime` - time of the order
- `origin_longitude` - longitude of the order
- `origin_latitude` - latitude of the order
- `m_order_eta` - time before order arrival
- `order_gk` - order number
- `order_status_key` - status, an enumeration consisting of the following mapping:
  * `4` - cancelled by client,
  * `9` - cancelled by system, i.e., a reject
- `is_driver_assigned_key` - whether a driver has been assigned
- `cancellation_time_in_seconds` - how many seconds passed before cancellation

The data_offers data set is a simple map with 2 columns:
- `order_gk` - order number, associated with the same column from the orders data set
- `offer_id` - ID of an offer

<a name="ex"></a>
## 3. Exploratory Data Analysis

sometext

<a name="con"></a>
## 4. Conclusion

sometext
