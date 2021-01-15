---
product: experience platform
title: Create offer activities
description: Learn how to create offer activities
page-status-flag: never-activated
uuid: a98ebc36-172d-4f46-b6ee-b2636a1007c9
contentOwner:
products:
audience:
content-type: reference
discoiquuid: 2590d94c-51ef-4c0f-b1ec-c2837e94da40
internal: n
snippet: y
---

# Create offer activities {#create-offer-activities}

Offer activities are containers for your offers that will leverage the Offer Decision Engine in order to pick the best offer to deliver, depending on the target of the delivery.

![](assets/do-not-localize/how-to-video.png) [Discover this feature in video](#video)

The list of offer activities is accessible in the **[!UICONTROL Activities]** menu. Filters are available to help you retrieve activities according to their status or start and end dates.

![](assets/activities-list.png)

To create an offer activity, follow these steps:

1. Make sure that the components below have been created in the Offer Library:

    * [Placements](offer-library/using/creating-placements.md),
    * [Collections](offer-library/using/creating-collections.md),
    * [Personalized offers](offer-library/using/creating-personalized-offers.md),
    * [Fallback offers](offer-library/using/creating-fallback-offers.md).

1. Select the **[!UICONTROL Activities]** menu, then click **[!UICONTROL Create activity]**.

1. Specify the activity's name as well as its start and end date and time, then click **[!UICONTROL Next]**.

    ![](assets/activities-name.png)

1. Drag and drop a placement from the list to add it to the activity, then click **[!UICONTROL Add collection]**.

    ![](assets/activities-placement.png)

1. Select the collection that contains the offers to consider, then click **[!UICONTROL Add]**.

    ![](assets/activities-collection.png)

1. The selected offers are added to the placement. Click **[!UICONTROL Next]** to confirm.

    In this example, we selected two offers that will display into a JSON-type placement aimed at presenting offers into a call center solution.

    ![](assets/offers-added.png)

1. Select the fallback offer that will be presented as a last resort to the customers that do not match the offers eligibility rules and constraints, then click **[!UICONTROL Next]**.

    ![](assets/add-fallback-offer.png)

1. If everything is configured properly and your activity is ready to be used to  present offers to customers, click **[!UICONTROL Finish]**, then select **[!UICONTROL Save and activate]**.

    You can also save the activity as draft, in order to edit and activate it later on.

    ![](assets/save-activities.png)

1. The activity displays in the list with the **[!UICONTROL Live]** or **[!UICONTROL Draft]** status, depending on whether you activated it or not in the previous step.

    It is now ready to be used to deliver offers to customers. You can select it to display its properties and edit or suppress it.

    ![](assets/activities-created.png)

## Tutorial video {#video}

>[!VIDEO](https://video.tv.adobe.com/v/329606?quality=12)
