swagger: "2.0"
x-collection-name: Broadleaf Commerce
x-complete: 1
info:
  title: Broadleaf Commerce API
  description: the-default-broadleaf-commerce-apis
  version: 1.0.0
host: demo.broadleafcommerce.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /cart/{cartId}/items/{itemId}:
    put:
      summary: Put Cart Items
      description: Put cart items.
      operationId: putCartCartItemsItem
      x-api-path-slug: cartcartiditemsitemid-put
      parameters:
      - in: path
        name: cartId
        description: cartId
      - in: query
        name: customerId
      - in: path
        name: itemId
        description: itemId
      - in: query
        name: priceOrder
        description: priceOrder
      - in: query
        name: quantity
        description: quantity
      responses:
        200:
          description: OK
      tags:
      - Cart
      - Items
    delete:
      summary: Delete Cart Items
      description: Delete cart items.
      operationId: deleteCartCartItemsItem
      x-api-path-slug: cartcartiditemsitemid-delete
      parameters:
      - in: path
        name: cartId
        description: cartId
      - in: query
        name: customerId
      - in: path
        name: itemId
        description: itemId
      - in: query
        name: priceOrder
        description: priceOrder
      responses:
        200:
          description: OK
      tags:
      - Cart
      - Items
  /wishlist/items/{itemId}:
    put:
      summary: Put Wishlist Items
      description: Put wishlist items.
      operationId: putWishlistItemsItem
      x-api-path-slug: wishlistitemsitemid-put
      parameters:
      - in: path
        name: itemId
        description: itemId
      - in: query
        name: quantity
        description: quantity
      - in: query
        name: wishlistName
        description: wishlistName
      responses:
        200:
          description: OK
      tags:
      - Wishlist
      - Items
    delete:
      summary: Delete Wishlist Items
      description: Delete wishlist items.
      operationId: deleteWishlistItemsItem
      x-api-path-slug: wishlistitemsitemid-delete
      parameters:
      - in: path
        name: itemId
        description: itemId
      - in: query
        name: wishlistName
        description: wishlistName
      responses:
        200:
          description: OK
      tags:
      - Wishlist
      - Items
  /wishlist/items/{itemId}/move:
    post:
      summary: Post Wishlist Items Move
      description: Post wishlist items move.
      operationId: postWishlistItemsItemMove
      x-api-path-slug: wishlistitemsitemidmove-post
      parameters:
      - in: path
        name: itemId
        description: itemId
      - in: query
        name: wishlistName
        description: wishlistName
      responses:
        200:
          description: OK
      tags:
      - Wishlist
      - Items
      - Move
  /cart/{cartId}/item:
    post:
      summary: Post Cart Item
      description: Post cart item.
      operationId: postCartCartItem
      x-api-path-slug: cartcartiditem-post
      parameters:
      - in: path
        name: cartId
        description: cartId
      - in: query
        name: customerId
      - in: body
        name: orderItemWrapper
        description: orderItemWrapper
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: priceOrder
        description: priceOrder
      responses:
        200:
          description: OK
      tags:
      - Cart
      - Item
  /cart/{cartId}/item/{itemId}/attributes:
    put:
      summary: Put Cart Item Attributes
      description: Put cart item attributes.
      operationId: putCartCartItemItemAttributes
      x-api-path-slug: cartcartiditemitemidattributes-put
      parameters:
      - in: path
        name: cartId
        description: cartId
      - in: query
        name: customerId
      - in: path
        name: itemId
        description: itemId
      - in: query
        name: priceOrder
        description: priceOrder
      - in: body
        name: requestParams
        description: requestParams
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Cart
      - Item
      - Attributes
    delete:
      summary: Delete Cart Item Attributes
      description: Delete cart item attributes.
      operationId: deleteCartCartItemItemAttributes
      x-api-path-slug: cartcartiditemitemidattributes-delete
      parameters:
      - in: path
        name: cartId
        description: cartId
      - in: query
        name: customerId
      - in: path
        name: itemId
        description: itemId
      - in: query
        name: priceOrder
        description: priceOrder
      - in: body
        name: requestParams
        description: requestParams
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Cart
      - Item
      - Attributes
  /shipping/{cartId}/group/{fulfillmentGroupId}/item:
    post:
      summary: Post Shipping Group Fulfillmentgroupid Item
      description: Post shipping group fulfillmentgroupid item.
      operationId: postShippingCartGroupFulfillmentgroupItem
      x-api-path-slug: shippingcartidgroupfulfillmentgroupiditem-post
      parameters:
      - in: path
        name: cartId
        description: cartId
      - in: path
        name: fulfillmentGroupId
        description: fulfillmentGroupId
      - in: query
        name: priceOrder
        description: priceOrder
      - in: body
        name: wrapper
        description: wrapper
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Shipping
      - Group
      - Fulfillmentgroupid
      - Item
  /shipping/{cartId}/group/{fulfillmentGroupId}/item/{itemId}:
    delete:
      summary: Delete Shipping Group Fulfillmentgroupid Item
      description: Delete shipping group fulfillmentgroupid item.
      operationId: deleteShippingCartGroupFulfillmentgroupItemItem
      x-api-path-slug: shippingcartidgroupfulfillmentgroupiditemitemid-delete
      parameters:
      - in: path
        name: cartId
        description: cartId
      - in: path
        name: fulfillmentGroupId
        description: fulfillmentGroupId
      - in: path
        name: itemId
        description: itemId
      responses:
        200:
          description: OK
      tags:
      - Shipping
      - Group
      - Fulfillmentgroupid
      - Item
  /wishlist/configure-item:
    post:
      summary: Post Wishlist Configure Item
      description: Post wishlist configure item.
      operationId: postWishlistConfigureItem
      x-api-path-slug: wishlistconfigureitem-post
      parameters:
      - in: body
        name: orderItemWrapper
        description: orderItemWrapper
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: wishlistName
        description: wishlistName
      responses:
        200:
          description: OK
      tags:
      - Wishlist
      - Configure
      - Item
  /wishlist/item:
    post:
      summary: Post Wishlist Item
      description: Post wishlist item.
      operationId: postWishlistItem
      x-api-path-slug: wishlistitem-post
      parameters:
      - in: body
        name: orderItemWrapper
        description: orderItemWrapper
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: wishlistName
        description: wishlistName
      responses:
        200:
          description: OK
      tags:
      - Wishlist
      - Item