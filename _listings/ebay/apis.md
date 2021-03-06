---
name: eBay
x-slug: ebay
description: Buy and sell electronics, cars, fashion apparel, collectibles, sporting
  goods, digital cameras, baby items, coupons, and everything else on eBay, the worlds
  online marketplace
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
x-kinRank: "8"
x-alexaRank: "42"
tags: Items
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/apis.md
specificationVersion: "0.14"
apis:
- name: Ebay - Get Item Get Items By Item Group
  x-api-slug: itemget-items-by-item-group-get
  description: This call retrieves the details of the individual items in an item
    group. An item group is an item that has various aspect differences, such as color,
    size, storage capacity, etc. You pass in the item group Id as a URI parameter.
    You use this call to show the item details of items with multiple aspects, such
    as color, size, storage capacity, etc. This call returns two main containers;
    items and commonDescriptions. The items container has an array of containers with
    the details of each item in the group. The commonDescriptions container has an
    array of containers for a description and the item Ids of all the items that have
    this exact description. Because items within an item group often have the same
    description, this decreases the size of the response. Request headers You will
    want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are
    an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-openapi.md
- name: Ebay - Get Item Get Item By Legacy
  x-api-slug: itemget-item-by-legacy-id-get
  description: This call is a bridge between the eBay legacy APIs, such as Trading,
    Shopping, and Finding and the eBay Buy APIs. There are differences between how
    legacy APIs and RESTful APIs return the identifier of an &quot;item&quot;. There
    is also a difference in what the item Id represents and in the format of the item
    Id value returned. This call lets you use the legacy item Ids retrieve the details
    of a specific item, such as description, price, and other information the buyer
    needs to make a purchasing decision. It also returns the RESTful item Id, which
    you can use with all the Buy API calls. For more information about how to use
    legacy Ids with the Buy APIs, see Legacy API compatibility in the Buying Integration
    guide. This call returns the item details and requires you to pass in either the
    item Id of a non-variation item or the item Ids of both the parent and child of
    a item group. An item group is an item that has various aspect differences, such
    as color, size, storage capacity, etc. When an item group is created, one of the
    item variations, such as the red shirt size L, is chosen as the &quot;parent&quot;.
    All the other items in the group are the children, such as the blue shirt size
    L, red shirt size M, etc. The fieldgroups URI parameter lets you control what
    is returned in the response. Setting fieldgroups to PRODUCT, adds additional fields
    to the default response that return information about the product of the item.
    For more information, see fieldgroups. Request headers You will want to use the
    X-EBAY-C-ENDUSERCTX request header with this call. If you are an eBay Network
    Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-item-by-legacy-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-item-by-legacy-id-get-openapi.md
- name: Ebay - Get Item Get Items By Item Group
  x-api-slug: itemget-items-by-item-group-get
  description: This call retrieves the details of the individual items in an item
    group. An item group is an item that has various aspect differences, such as color,
    size, storage capacity, etc. You pass in the item group Id as a URI parameter.
    You use this call to show the item details of items with multiple aspects, such
    as color, size, storage capacity, etc. This call returns two main containers;
    items and commonDescriptions. The items container has an array of containers with
    the details of each item in the group. The commonDescriptions container has an
    array of containers for a description and the item Ids of all the items that have
    this exact description. Because items within an item group often have the same
    description, this decreases the size of the response. Request headers You will
    want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are
    an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-openapi.md
- name: Ebay - Get Item Item
  x-api-slug: itemitem-id-get
  description: This call retrieves the details of a specific item, such as description,
    price, category, all item aspects, condition, return policies, seller feedback
    and score, shipping options, shipping costs, estimated delivery, and other information
    the buyer needs to make a purchasing decision. The Buy APIs are designed to let
    you create an eBay shopping experience in your app or website. This means you
    will need to know when something, such as the availability, quantity, etc., has
    changed in any eBay item you are offering. You can do this easily by setting the
    fieldgroups URI parameter. This parameter lets you control what is returned in
    the response. Setting fieldgroups to COMPACT reduces the response to only the
    five fields that you need in order to check if any item detail has changed. Setting
    fieldgroups to PRODUCT, adds additional fields to the default response that return
    information about the product of the item. You can use either COMPACT or PRODUCT
    but not both. For more information, see fieldgroups. Request headers You will
    want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are
    an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemitem-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemitem-id-get-openapi.md
- name: Ebay - Get Item Summary Search
  x-api-slug: item-summarysearch-get
  description: 'This call performs an advanced search for items. You can search by
    keyword, category, eBay product Id (EPID), or gtin. Or a combination of these.
    Encoding Parameters and Headers As with all query parameter values, the fields
    parameter value and request header values must be URL encoded. For better readability,
    the examples in this document omit the encoding. Example: &nbsp;&nbsp;search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{Nike|Wilson} Encoded
    Example: &nbsp;&nbsp; search?q=world cup soccer ball&amp;aspect_filter=categoryId%3A20863%2CBrand%3A%7BNike%7CWilson%7D
    For more information about encoding, see HTML URL Encoding Reference The following
    are examples of using filters: The following call returns 4,330,774 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone
    This call, which limits the results to the category &quot;Cell Phones &amp; Smartphones&quot;,
    returns 142,098 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone&amp;category_ids=9355
    These calls, which limit results to a Samsung Galaxy S5, returns 97 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone&amp;category_ids=220&amp;epid=182527490
    &nbsp;&nbsp;&nbsp;or &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?epid=182527490
    Controlling what is returned You can also control what is returned by using the
    fieldgroups field. In addition to returning items, which is the default, you can
    return refinements (metadata) about an item that enables you to create aspect
    histograms. A histogram enables users to drill down in each refinement narrowing
    the search results. You can return: ASPECT_REFINEMENTS - Lets shoppers refine
    the result set by variation aspects, such as Brand, Color, etc. BUYING_OPTION_REFINEMENT
    - Lets shoppers refine the result set by either FIXED_PRICE or AUCTION CATEGORY_REFINEMENTS
    - Lets shoppers refine the result set by items in a category CONDITION_REFINEMENT
    - Lets shoppers refine the result set by item condition, such as NEW, USED, etc.
    MATCHING_ITEMS - The default, which returns the items. When used with one or more
    of the refinement values above the specified refinements and all the matching
    items are returned. FULL - This returns all the refinement containers and all
    the matching items. Filtering by aspects You can use the aspect refinements returned
    to filter the result set using the aspect_filter field. For example: This call
    gets a list of the aspects pairs for the item and the dominant category (category
    most of the items are in). /buy/browse/v1/item_summary/search?q=world cup soccer
    ball&amp;fieldgroups=ASPECT_REFINEMENTS This call filters the items by one of
    the aspect pairs returned and the dominant category ( categoryId is required when
    using aspect_filter) /buy/browse/v1/item_summary/search?q=world cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{adidas}
    This call filters the items by multiple aspects /buy/browse/v1/item_summary/search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{adidas},Featured Refinements:{Adidas
    Match Ball} This call filters the items by multiple aspect values /buy/browse/v1/item_summary/search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{Nike|Wilson} Additional
    filters There are also multiple filters you can use to refine the result set,
    such as listing format, item condition, price range, listing end date, location,
    and more. You can use multiple filters in a single call. For a list and details
    of the supported filters, see search Call Field Filters. Pagination and sort controls
    There are pagination controls ( limit and offset fields) and sort query parameter
    that control/sort the data that is returned. By default, the results are sorted
    by &quot;Best Match&quot;. For more information about Best Match, see the eBay
    help page Best Match. Request headers You will want to use the X-EBAY-C-ENDUSERCTX
    request header with this call. If you are an eBay Network Partner you must use
    affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId in the header
    in order to be paid for selling eBay items on your site and it is strongly recommended
    you use contextualLocation to improved the estimated delivery window information.
    For details see, Request headers in the Buy APIs Overview. Restrictions For a
    list of supported sites and other restrictions, see API Restrictions. Limitation:
    This call can return a maximum of 10,000 items.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-summarysearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-summarysearch-get-openapi.md
- name: Ebay - Get Item
  x-api-slug: item-get
  description: 'The Item feed file is generated each day. This call lets you download
    a daily TSV_GZIP (tab separated value gzip) Item feed file of all the items that
    were listed on a specific day in a specific category. For each item, all the item
    details are returned, except for the item description. The description of each
    item is excluded because these can be huge and items in an item group (an item
    with variations, such as size and color) can share the same description. The item
    descriptions are returned in a separate Descriptions gzip feed file by the getItemDescriptionFeed
    call. To store the complete item details, you would always run the getItemFeed
    and getItemDescriptionFeed calls with the same parameters. &nbsp;&nbsp;&nbsp;
    /item?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918 &nbsp;&nbsp;&nbsp;
    /item_description?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
    Items returned in the feed file All items in the file are: In new condition Fixed
    price (Buy It Now); no auctions From eBay trusted sellers The feed file contains
    all the items from all the child categories of the specified category. The first
    line of the file is the header, which indicates the order of the values on each
    line. Each header is described in the Response fields section on this page. Downloading
    feed files Item feed files are binary gzip files. If the file is larger than 100
    MB, the download must be streamed in chunks. You specify the size of the chunks
    in bytes using the Range request header. The Content-range response header indicates
    where in the full resource this partial chunk of data belongs and the total number
    of bytes in the file. For more information about using these headers, see Retrieving
    a gzip feed file. Important: The response is always a TSV_GZIP file. But for documentation
    purposes, the response is shown as JSON fields so that the value returned in each
    column can be explained. The order of the response fields, shows you the order
    of the columns in the feed file. Restrictions For a list of supported sites and
    other restrictions, see API Restrictions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-get-openapi.md
- name: Ebay - Get Item Description
  x-api-slug: item-description-get
  description: 'The Description feed file is generated each day. This call lets you
    download a daily TSV_GZIP (tab separated value gzip) Description feed file containing
    the descriptions of all the items that were listed on a specific day in a specific
    category. To store the complete item details, you would always run the getItemFeed
    and getItemDescriptionFeed calls with the same parameters. &nbsp;&nbsp;&nbsp;
    /item?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918 &nbsp;&nbsp;&nbsp;
    /item_description?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
    Combining the Description and Item feed files The Description feed file contains
    only the itemId, itemGroupId and description columns. The value of the description
    column is BASE64 encoded. For each row, there will be values in either itemId
    or itemGroupId. The description column will always contain a value. itemGroupId
    - The value in this column is the ID of an item group (an item with variations,
    such as size and color) where the items in the group share the same description.
    Even though the itemGroupId represents more than one item, the itemGroupId and
    description are returned only once for the entire group. In this case, there will
    be values in the itemGroupId and description columns. You match the value of itemGroupId
    from the Description feed file with the value of primaryItemGroupId from the Item
    feed file for the same day and category. itemId - The value in this column is
    the ID of an item that is not part of an item group or (in rare cases) the item
    is part of an item group but does not share a description with other items in
    the group. In this case, there will be values in the itemId and description columns.
    You match the value of itemId from the Description feed file with the value of
    itemId from the Item feed file for the same day and category. The file will contain
    the descriptions for all the items or item groups from all the child categories
    of the category. The first line of the file is the header, which indicates the
    order of the values on each line. Each column is described in the Response fields
    section on this page. Downloading feed files Description feed files are very large
    so the gzip file, which is binary, is streamed in chunks. You specify the size
    of the chunks in bytes using the Range request header. The Content-range response
    header indicates where in the full resource this partial chunk of data belongs
    and the total number of bytes in the file. For more information about using these
    headers, see Retrieving a gzip feed file. Important: The response is always a
    TSV_GZIP file. But for documentation purposes, the response is shown as JSON fields
    so that the value returned in each column can be explained. The order of the response
    fields, shows you the order of the columns in the feed file. Restrictions For
    a list of supported sites and other restrictions, see API Restrictions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-description-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-description-get-openapi.md
- name: Ebay - Get Category Tree Category Tree  Get Item Aspects For Category
  x-api-slug: category-treecategory-tree-idget-item-aspects-for-category-get
  description: 'This call returns a list of aspects that are appropriate or necessary
    for accurately describing items in the specified leaf category. Each aspect identifies
    an item attribute (for example, color) for which the seller will be required or
    encouraged to provide a value (or variation values) when offering an item in that
    category on eBay. For each aspect, getItemAspectsForCategory provides complete
    metadata, including: The aspect''s data type, format, and entry mode Whether the
    aspect is required in listings Whether the aspect can be used for item variations
    Whether the aspect accepts multiple values for an item Allowed values for the
    aspectUse this information to construct an interface through which sellers can
    enter or select the appropriate values for their items or item variations. Once
    you collect those values, include them as product aspects when creating inventory
    items using the Inventory API.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-openapi.md
- name: Ebay - Get Item Get Item By Legacy
  x-api-slug: itemget-item-by-legacy-id-get
  description: This call is a bridge between the eBay legacy APIs, such as Trading,
    Shopping, and Finding and the eBay Buy APIs. There are differences between how
    legacy APIs and RESTful APIs return the identifier of an &quot;item&quot;. There
    is also a difference in what the item Id represents and in the format of the item
    Id value returned. This call lets you use the legacy item Ids retrieve the details
    of a specific item, such as description, price, and other information the buyer
    needs to make a purchasing decision. It also returns the RESTful item Id, which
    you can use with all the Buy API calls. For more information about how to use
    legacy Ids with the Buy APIs, see Legacy API compatibility in the Buying Integration
    guide. This call returns the item details and requires you to pass in either the
    item Id of a non-variation item or the item Ids of both the parent and child of
    a item group. An item group is an item that has various aspect differences, such
    as color, size, storage capacity, etc. When an item group is created, one of the
    item variations, such as the red shirt size L, is chosen as the &quot;parent&quot;.
    All the other items in the group are the children, such as the blue shirt size
    L, red shirt size M, etc. The fieldgroups URI parameter lets you control what
    is returned in the response. Setting fieldgroups to PRODUCT, adds additional fields
    to the default response that return information about the product of the item.
    For more information, see fieldgroups. Request headers You will want to use the
    X-EBAY-C-ENDUSERCTX request header with this call. If you are an eBay Network
    Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-item-by-legacy-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-item-by-legacy-id-get-openapi.md
- name: Ebay - Get Item Get Items By Item Group
  x-api-slug: itemget-items-by-item-group-get
  description: This call retrieves the details of the individual items in an item
    group. An item group is an item that has various aspect differences, such as color,
    size, storage capacity, etc. You pass in the item group Id as a URI parameter.
    You use this call to show the item details of items with multiple aspects, such
    as color, size, storage capacity, etc. This call returns two main containers;
    items and commonDescriptions. The items container has an array of containers with
    the details of each item in the group. The commonDescriptions container has an
    array of containers for a description and the item Ids of all the items that have
    this exact description. Because items within an item group often have the same
    description, this decreases the size of the response. Request headers You will
    want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are
    an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-openapi.md
- name: Ebay - Get Item Item
  x-api-slug: itemitem-id-get
  description: This call retrieves the details of a specific item, such as description,
    price, category, all item aspects, condition, return policies, seller feedback
    and score, shipping options, shipping costs, estimated delivery, and other information
    the buyer needs to make a purchasing decision. The Buy APIs are designed to let
    you create an eBay shopping experience in your app or website. This means you
    will need to know when something, such as the availability, quantity, etc., has
    changed in any eBay item you are offering. You can do this easily by setting the
    fieldgroups URI parameter. This parameter lets you control what is returned in
    the response. Setting fieldgroups to COMPACT reduces the response to only the
    five fields that you need in order to check if any item detail has changed. Setting
    fieldgroups to PRODUCT, adds additional fields to the default response that return
    information about the product of the item. You can use either COMPACT or PRODUCT
    but not both. For more information, see fieldgroups. Request headers You will
    want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are
    an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemitem-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemitem-id-get-openapi.md
- name: Ebay - Get Item Summary Search
  x-api-slug: item-summarysearch-get
  description: 'This call performs an advanced search for items. You can search by
    keyword, category, eBay product Id (EPID), or gtin. Or a combination of these.
    Encoding Parameters and Headers As with all query parameter values, the fields
    parameter value and request header values must be URL encoded. For better readability,
    the examples in this document omit the encoding. Example: &nbsp;&nbsp;search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{Nike|Wilson} Encoded
    Example: &nbsp;&nbsp; search?q=world cup soccer ball&amp;aspect_filter=categoryId%3A20863%2CBrand%3A%7BNike%7CWilson%7D
    For more information about encoding, see HTML URL Encoding Reference The following
    are examples of using filters: The following call returns 4,330,774 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone
    This call, which limits the results to the category &quot;Cell Phones &amp; Smartphones&quot;,
    returns 142,098 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone&amp;category_ids=9355
    These calls, which limit results to a Samsung Galaxy S5, returns 97 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone&amp;category_ids=220&amp;epid=182527490
    &nbsp;&nbsp;&nbsp;or &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?epid=182527490
    Controlling what is returned You can also control what is returned by using the
    fieldgroups field. In addition to returning items, which is the default, you can
    return refinements (metadata) about an item that enables you to create aspect
    histograms. A histogram enables users to drill down in each refinement narrowing
    the search results. You can return: ASPECT_REFINEMENTS - Lets shoppers refine
    the result set by variation aspects, such as Brand, Color, etc. BUYING_OPTION_REFINEMENT
    - Lets shoppers refine the result set by either FIXED_PRICE or AUCTION CATEGORY_REFINEMENTS
    - Lets shoppers refine the result set by items in a category CONDITION_REFINEMENT
    - Lets shoppers refine the result set by item condition, such as NEW, USED, etc.
    MATCHING_ITEMS - The default, which returns the items. When used with one or more
    of the refinement values above the specified refinements and all the matching
    items are returned. FULL - This returns all the refinement containers and all
    the matching items. Filtering by aspects You can use the aspect refinements returned
    to filter the result set using the aspect_filter field. For example: This call
    gets a list of the aspects pairs for the item and the dominant category (category
    most of the items are in). /buy/browse/v1/item_summary/search?q=world cup soccer
    ball&amp;fieldgroups=ASPECT_REFINEMENTS This call filters the items by one of
    the aspect pairs returned and the dominant category ( categoryId is required when
    using aspect_filter) /buy/browse/v1/item_summary/search?q=world cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{adidas}
    This call filters the items by multiple aspects /buy/browse/v1/item_summary/search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{adidas},Featured Refinements:{Adidas
    Match Ball} This call filters the items by multiple aspect values /buy/browse/v1/item_summary/search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{Nike|Wilson} Additional
    filters There are also multiple filters you can use to refine the result set,
    such as listing format, item condition, price range, listing end date, location,
    and more. You can use multiple filters in a single call. For a list and details
    of the supported filters, see search Call Field Filters. Pagination and sort controls
    There are pagination controls ( limit and offset fields) and sort query parameter
    that control/sort the data that is returned. By default, the results are sorted
    by &quot;Best Match&quot;. For more information about Best Match, see the eBay
    help page Best Match. Request headers You will want to use the X-EBAY-C-ENDUSERCTX
    request header with this call. If you are an eBay Network Partner you must use
    affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId in the header
    in order to be paid for selling eBay items on your site and it is strongly recommended
    you use contextualLocation to improved the estimated delivery window information.
    For details see, Request headers in the Buy APIs Overview. Restrictions For a
    list of supported sites and other restrictions, see API Restrictions. Limitation:
    This call can return a maximum of 10,000 items.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-summarysearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-summarysearch-get-openapi.md
- name: Ebay - Get Item
  x-api-slug: item-get
  description: 'The Item feed file is generated each day. This call lets you download
    a daily TSV_GZIP (tab separated value gzip) Item feed file of all the items that
    were listed on a specific day in a specific category. For each item, all the item
    details are returned, except for the item description. The description of each
    item is excluded because these can be huge and items in an item group (an item
    with variations, such as size and color) can share the same description. The item
    descriptions are returned in a separate Descriptions gzip feed file by the getItemDescriptionFeed
    call. To store the complete item details, you would always run the getItemFeed
    and getItemDescriptionFeed calls with the same parameters. &nbsp;&nbsp;&nbsp;
    /item?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918 &nbsp;&nbsp;&nbsp;
    /item_description?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
    Items returned in the feed file All items in the file are: In new condition Fixed
    price (Buy It Now); no auctions From eBay trusted sellers The feed file contains
    all the items from all the child categories of the specified category. The first
    line of the file is the header, which indicates the order of the values on each
    line. Each header is described in the Response fields section on this page. Downloading
    feed files Item feed files are binary gzip files. If the file is larger than 100
    MB, the download must be streamed in chunks. You specify the size of the chunks
    in bytes using the Range request header. The Content-range response header indicates
    where in the full resource this partial chunk of data belongs and the total number
    of bytes in the file. For more information about using these headers, see Retrieving
    a gzip feed file. Important: The response is always a TSV_GZIP file. But for documentation
    purposes, the response is shown as JSON fields so that the value returned in each
    column can be explained. The order of the response fields, shows you the order
    of the columns in the feed file. Restrictions For a list of supported sites and
    other restrictions, see API Restrictions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-get-openapi.md
- name: Ebay - Get Item Description
  x-api-slug: item-description-get
  description: 'The Description feed file is generated each day. This call lets you
    download a daily TSV_GZIP (tab separated value gzip) Description feed file containing
    the descriptions of all the items that were listed on a specific day in a specific
    category. To store the complete item details, you would always run the getItemFeed
    and getItemDescriptionFeed calls with the same parameters. &nbsp;&nbsp;&nbsp;
    /item?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918 &nbsp;&nbsp;&nbsp;
    /item_description?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
    Combining the Description and Item feed files The Description feed file contains
    only the itemId, itemGroupId and description columns. The value of the description
    column is BASE64 encoded. For each row, there will be values in either itemId
    or itemGroupId. The description column will always contain a value. itemGroupId
    - The value in this column is the ID of an item group (an item with variations,
    such as size and color) where the items in the group share the same description.
    Even though the itemGroupId represents more than one item, the itemGroupId and
    description are returned only once for the entire group. In this case, there will
    be values in the itemGroupId and description columns. You match the value of itemGroupId
    from the Description feed file with the value of primaryItemGroupId from the Item
    feed file for the same day and category. itemId - The value in this column is
    the ID of an item that is not part of an item group or (in rare cases) the item
    is part of an item group but does not share a description with other items in
    the group. In this case, there will be values in the itemId and description columns.
    You match the value of itemId from the Description feed file with the value of
    itemId from the Item feed file for the same day and category. The file will contain
    the descriptions for all the items or item groups from all the child categories
    of the category. The first line of the file is the header, which indicates the
    order of the values on each line. Each column is described in the Response fields
    section on this page. Downloading feed files Description feed files are very large
    so the gzip file, which is binary, is streamed in chunks. You specify the size
    of the chunks in bytes using the Range request header. The Content-range response
    header indicates where in the full resource this partial chunk of data belongs
    and the total number of bytes in the file. For more information about using these
    headers, see Retrieving a gzip feed file. Important: The response is always a
    TSV_GZIP file. But for documentation purposes, the response is shown as JSON fields
    so that the value returned in each column can be explained. The order of the response
    fields, shows you the order of the columns in the feed file. Restrictions For
    a list of supported sites and other restrictions, see API Restrictions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-description-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-description-get-openapi.md
- name: Ebay - Get Category Tree Category Tree  Get Item Aspects For Category
  x-api-slug: category-treecategory-tree-idget-item-aspects-for-category-get
  description: 'This call returns a list of aspects that are appropriate or necessary
    for accurately describing items in the specified leaf category. Each aspect identifies
    an item attribute (for example, color) for which the seller will be required or
    encouraged to provide a value (or variation values) when offering an item in that
    category on eBay. For each aspect, getItemAspectsForCategory provides complete
    metadata, including: The aspect''s data type, format, and entry mode Whether the
    aspect is required in listings Whether the aspect can be used for item variations
    Whether the aspect accepts multiple values for an item Allowed values for the
    aspectUse this information to construct an interface through which sellers can
    enter or select the appropriate values for their items or item variations. Once
    you collect those values, include them as product aspects when creating inventory
    items using the Inventory API.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-openapi.md
- name: Ebay - Get Category Tree Category Tree  Get Item Aspects For Category
  x-api-slug: category-treecategory-tree-idget-item-aspects-for-category-get
  description: 'This call returns a list of aspects that are appropriate or necessary
    for accurately describing items in the specified leaf category. Each aspect identifies
    an item attribute (for example, color) for which the seller will be required or
    encouraged to provide a value (or variation values) when offering an item in that
    category on eBay. For each aspect, getItemAspectsForCategory provides complete
    metadata, including: The aspect''s data type, format, and entry mode Whether the
    aspect is required in listings Whether the aspect can be used for item variations
    Whether the aspect accepts multiple values for an item Allowed values for the
    aspectUse this information to construct an interface through which sellers can
    enter or select the appropriate values for their items or item variations. Once
    you collect those values, include them as product aspects when creating inventory
    items using the Inventory API.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-openapi.md
- name: Ebay - Get Item Description
  x-api-slug: item-description-get
  description: 'The Description feed file is generated each day. This call lets you
    download a daily TSV_GZIP (tab separated value gzip) Description feed file containing
    the descriptions of all the items that were listed on a specific day in a specific
    category. To store the complete item details, you would always run the getItemFeed
    and getItemDescriptionFeed calls with the same parameters. &nbsp;&nbsp;&nbsp;
    /item?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918 &nbsp;&nbsp;&nbsp;
    /item_description?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
    Combining the Description and Item feed files The Description feed file contains
    only the itemId, itemGroupId and description columns. The value of the description
    column is BASE64 encoded. For each row, there will be values in either itemId
    or itemGroupId. The description column will always contain a value. itemGroupId
    - The value in this column is the ID of an item group (an item with variations,
    such as size and color) where the items in the group share the same description.
    Even though the itemGroupId represents more than one item, the itemGroupId and
    description are returned only once for the entire group. In this case, there will
    be values in the itemGroupId and description columns. You match the value of itemGroupId
    from the Description feed file with the value of primaryItemGroupId from the Item
    feed file for the same day and category. itemId - The value in this column is
    the ID of an item that is not part of an item group or (in rare cases) the item
    is part of an item group but does not share a description with other items in
    the group. In this case, there will be values in the itemId and description columns.
    You match the value of itemId from the Description feed file with the value of
    itemId from the Item feed file for the same day and category. The file will contain
    the descriptions for all the items or item groups from all the child categories
    of the category. The first line of the file is the header, which indicates the
    order of the values on each line. Each column is described in the Response fields
    section on this page. Downloading feed files Description feed files are very large
    so the gzip file, which is binary, is streamed in chunks. You specify the size
    of the chunks in bytes using the Range request header. The Content-range response
    header indicates where in the full resource this partial chunk of data belongs
    and the total number of bytes in the file. For more information about using these
    headers, see Retrieving a gzip feed file. Important: The response is always a
    TSV_GZIP file. But for documentation purposes, the response is shown as JSON fields
    so that the value returned in each column can be explained. The order of the response
    fields, shows you the order of the columns in the feed file. Restrictions For
    a list of supported sites and other restrictions, see API Restrictions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-description-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-description-get-openapi.md
- name: Ebay - Get Item
  x-api-slug: item-get
  description: 'The Item feed file is generated each day. This call lets you download
    a daily TSV_GZIP (tab separated value gzip) Item feed file of all the items that
    were listed on a specific day in a specific category. For each item, all the item
    details are returned, except for the item description. The description of each
    item is excluded because these can be huge and items in an item group (an item
    with variations, such as size and color) can share the same description. The item
    descriptions are returned in a separate Descriptions gzip feed file by the getItemDescriptionFeed
    call. To store the complete item details, you would always run the getItemFeed
    and getItemDescriptionFeed calls with the same parameters. &nbsp;&nbsp;&nbsp;
    /item?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918 &nbsp;&nbsp;&nbsp;
    /item_description?feed_scope=NEWLY_LISTED&amp;category_id=625&amp;date=20170918
    Items returned in the feed file All items in the file are: In new condition Fixed
    price (Buy It Now); no auctions From eBay trusted sellers The feed file contains
    all the items from all the child categories of the specified category. The first
    line of the file is the header, which indicates the order of the values on each
    line. Each header is described in the Response fields section on this page. Downloading
    feed files Item feed files are binary gzip files. If the file is larger than 100
    MB, the download must be streamed in chunks. You specify the size of the chunks
    in bytes using the Range request header. The Content-range response header indicates
    where in the full resource this partial chunk of data belongs and the total number
    of bytes in the file. For more information about using these headers, see Retrieving
    a gzip feed file. Important: The response is always a TSV_GZIP file. But for documentation
    purposes, the response is shown as JSON fields so that the value returned in each
    column can be explained. The order of the response fields, shows you the order
    of the columns in the feed file. Restrictions For a list of supported sites and
    other restrictions, see API Restrictions.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-get-openapi.md
- name: Ebay - Get Item Summary Search
  x-api-slug: item-summarysearch-get
  description: 'This call performs an advanced search for items. You can search by
    keyword, category, eBay product Id (EPID), or gtin. Or a combination of these.
    Encoding Parameters and Headers As with all query parameter values, the fields
    parameter value and request header values must be URL encoded. For better readability,
    the examples in this document omit the encoding. Example: &nbsp;&nbsp;search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{Nike|Wilson} Encoded
    Example: &nbsp;&nbsp; search?q=world cup soccer ball&amp;aspect_filter=categoryId%3A20863%2CBrand%3A%7BNike%7CWilson%7D
    For more information about encoding, see HTML URL Encoding Reference The following
    are examples of using filters: The following call returns 4,330,774 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone
    This call, which limits the results to the category &quot;Cell Phones &amp; Smartphones&quot;,
    returns 142,098 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone&amp;category_ids=9355
    These calls, which limit results to a Samsung Galaxy S5, returns 97 items. &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?q=phone&amp;category_ids=220&amp;epid=182527490
    &nbsp;&nbsp;&nbsp;or &nbsp;&nbsp;&nbsp;/buy/browse/v1/item_summary/search?epid=182527490
    Controlling what is returned You can also control what is returned by using the
    fieldgroups field. In addition to returning items, which is the default, you can
    return refinements (metadata) about an item that enables you to create aspect
    histograms. A histogram enables users to drill down in each refinement narrowing
    the search results. You can return: ASPECT_REFINEMENTS - Lets shoppers refine
    the result set by variation aspects, such as Brand, Color, etc. BUYING_OPTION_REFINEMENT
    - Lets shoppers refine the result set by either FIXED_PRICE or AUCTION CATEGORY_REFINEMENTS
    - Lets shoppers refine the result set by items in a category CONDITION_REFINEMENT
    - Lets shoppers refine the result set by item condition, such as NEW, USED, etc.
    MATCHING_ITEMS - The default, which returns the items. When used with one or more
    of the refinement values above the specified refinements and all the matching
    items are returned. FULL - This returns all the refinement containers and all
    the matching items. Filtering by aspects You can use the aspect refinements returned
    to filter the result set using the aspect_filter field. For example: This call
    gets a list of the aspects pairs for the item and the dominant category (category
    most of the items are in). /buy/browse/v1/item_summary/search?q=world cup soccer
    ball&amp;fieldgroups=ASPECT_REFINEMENTS This call filters the items by one of
    the aspect pairs returned and the dominant category ( categoryId is required when
    using aspect_filter) /buy/browse/v1/item_summary/search?q=world cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{adidas}
    This call filters the items by multiple aspects /buy/browse/v1/item_summary/search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{adidas},Featured Refinements:{Adidas
    Match Ball} This call filters the items by multiple aspect values /buy/browse/v1/item_summary/search?q=world
    cup soccer ball&amp;aspect_filter=categoryId:20863,Brand:{Nike|Wilson} Additional
    filters There are also multiple filters you can use to refine the result set,
    such as listing format, item condition, price range, listing end date, location,
    and more. You can use multiple filters in a single call. For a list and details
    of the supported filters, see search Call Field Filters. Pagination and sort controls
    There are pagination controls ( limit and offset fields) and sort query parameter
    that control/sort the data that is returned. By default, the results are sorted
    by &quot;Best Match&quot;. For more information about Best Match, see the eBay
    help page Best Match. Request headers You will want to use the X-EBAY-C-ENDUSERCTX
    request header with this call. If you are an eBay Network Partner you must use
    affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId in the header
    in order to be paid for selling eBay items on your site and it is strongly recommended
    you use contextualLocation to improved the estimated delivery window information.
    For details see, Request headers in the Buy APIs Overview. Restrictions For a
    list of supported sites and other restrictions, see API Restrictions. Limitation:
    This call can return a maximum of 10,000 items.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-summarysearch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/item-summarysearch-get-openapi.md
- name: Ebay - Get Item Item
  x-api-slug: itemitem-id-get
  description: This call retrieves the details of a specific item, such as description,
    price, category, all item aspects, condition, return policies, seller feedback
    and score, shipping options, shipping costs, estimated delivery, and other information
    the buyer needs to make a purchasing decision. The Buy APIs are designed to let
    you create an eBay shopping experience in your app or website. This means you
    will need to know when something, such as the availability, quantity, etc., has
    changed in any eBay item you are offering. You can do this easily by setting the
    fieldgroups URI parameter. This parameter lets you control what is returned in
    the response. Setting fieldgroups to COMPACT reduces the response to only the
    five fields that you need in order to check if any item detail has changed. Setting
    fieldgroups to PRODUCT, adds additional fields to the default response that return
    information about the product of the item. You can use either COMPACT or PRODUCT
    but not both. For more information, see fieldgroups. Request headers You will
    want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are
    an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemitem-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemitem-id-get-openapi.md
- name: Ebay - Get Item Get Items By Item Group
  x-api-slug: itemget-items-by-item-group-get
  description: This call retrieves the details of the individual items in an item
    group. An item group is an item that has various aspect differences, such as color,
    size, storage capacity, etc. You pass in the item group Id as a URI parameter.
    You use this call to show the item details of items with multiple aspects, such
    as color, size, storage capacity, etc. This call returns two main containers;
    items and commonDescriptions. The items container has an array of containers with
    the details of each item in the group. The commonDescriptions container has an
    array of containers for a description and the item Ids of all the items that have
    this exact description. Because items within an item group often have the same
    description, this decreases the size of the response. Request headers You will
    want to use the X-EBAY-C-ENDUSERCTX request header with this call. If you are
    an eBay Network Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-items-by-item-group-get-openapi.md
- name: Ebay - Get Item Get Item By Legacy
  x-api-slug: itemget-item-by-legacy-id-get
  description: This call is a bridge between the eBay legacy APIs, such as Trading,
    Shopping, and Finding and the eBay Buy APIs. There are differences between how
    legacy APIs and RESTful APIs return the identifier of an &quot;item&quot;. There
    is also a difference in what the item Id represents and in the format of the item
    Id value returned. This call lets you use the legacy item Ids retrieve the details
    of a specific item, such as description, price, and other information the buyer
    needs to make a purchasing decision. It also returns the RESTful item Id, which
    you can use with all the Buy API calls. For more information about how to use
    legacy Ids with the Buy APIs, see Legacy API compatibility in the Buying Integration
    guide. This call returns the item details and requires you to pass in either the
    item Id of a non-variation item or the item Ids of both the parent and child of
    a item group. An item group is an item that has various aspect differences, such
    as color, size, storage capacity, etc. When an item group is created, one of the
    item variations, such as the red shirt size L, is chosen as the &quot;parent&quot;.
    All the other items in the group are the children, such as the blue shirt size
    L, red shirt size M, etc. The fieldgroups URI parameter lets you control what
    is returned in the response. Setting fieldgroups to PRODUCT, adds additional fields
    to the default response that return information about the product of the item.
    For more information, see fieldgroups. Request headers You will want to use the
    X-EBAY-C-ENDUSERCTX request header with this call. If you are an eBay Network
    Partner you must use affiliateCampaignId=ePNCampaignId,affiliateReferenceId=referenceId
    in the header in order to be paid for selling eBay items on your site and it is
    strongly recommended you use contextualLocation to improved the estimated delivery
    window information. For details see, Request headers in the Buy APIs Overview.
    Restrictions For a list of supported sites and other restrictions, see API Restrictions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Commerce, Stack, internet, Marketplace, Technology, API Provider, Auctions,
    Profiles, General Data, Relative Data, Service API, Pedestal, Historical Data
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-item-by-legacy-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/items/master/_listings/ebay/itemget-item-by-legacy-id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://easycron.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ebay.stack.network
- type: x-blog
  url: https://go.developer.ebay.com/dev-program-blog
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ebay
- type: x-crunchbase
  url: https://crunchbase.com/organization/leah
- type: x-developer
  url: https://go.developer.ebay.com/
- type: x-email
  url: spam@ebay.com
- type: x-email
  url: spoof@ebay.com
- type: x-github
  url: https://github.com/eBayDeveloper
- type: x-twitter
  url: https://twitter.com/eBay
- type: x-twitter
  url: https://twitter.com/ebaydev
- type: x-website
  url: https://ebay.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---