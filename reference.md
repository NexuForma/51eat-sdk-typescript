# Reference
## Business: Messaging
<details><summary><code>client.businessMessaging.<a href="/src/api/resources/businessMessaging/client/Client.ts">searchBusinessConversations</a>({ ...params }) -> FiveOneEat.SearchBusinessConversationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.businessMessaging.searchBusinessConversations({
    q: "john"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.SearchBusinessConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessMessagingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business: Products
<details><summary><code>client.businessProducts.<a href="/src/api/resources/businessProducts/client/Client.ts">adjustVariantInventory</a>({ ...params }) -> FiveOneEat.AdjustVariantInventoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.businessProducts.adjustVariantInventory({
    variant: "variant",
    type: "add",
    quantity: 1,
    reason: "restock"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.AdjustInventoryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProducts.<a href="/src/api/resources/businessProducts/client/Client.ts">listVariantInventoryHistory</a>({ ...params }) -> FiveOneEat.ListVariantInventoryHistoryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.businessProducts.listVariantInventoryHistory({
    variant: "variant"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.ListVariantInventoryHistoryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProducts.<a href="/src/api/resources/businessProducts/client/Client.ts">getProductInventorySummary</a>({ ...params }) -> FiveOneEat.GetProductInventorySummaryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.businessProducts.getProductInventorySummary({
    product: "product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.GetProductInventorySummaryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer: Events
<details><summary><code>client.customerEvents.<a href="/src/api/resources/customerEvents/client/Client.ts">releaseTicketHold</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Release the TicketCart holds for the authenticated user and event.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerEvents.releaseTicketHold({
    eventId: "eventId",
    cartId: "cartId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.ReleaseTicketHoldRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerEventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer: Messaging
<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">searchCustomerConversations</a>({ ...params }) -> FiveOneEat.SearchCustomerConversationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerMessaging.searchCustomerConversations({
    q: "pizza"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.SearchCustomerConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerMessagingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer: My Account
<details><summary><code>client.customerMyAccount.<a href="/src/api/resources/customerMyAccount/client/Client.ts">getMyTicket</a>({ ...params }) -> FiveOneEat.GetMyTicketResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a single ticket belonging to the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerMyAccount.getMyTicket({
    ticketId: "ticketId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.GetMyTicketRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerMyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customerMyAccount.<a href="/src/api/resources/customerMyAccount/client/Client.ts">getMyTicketOrder</a>({ ...params }) -> FiveOneEat.GetMyTicketOrderResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a single ticket order belonging to the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customerMyAccount.getMyTicketOrder({
    orderId: "orderId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.GetMyTicketOrderRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerMyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer
<details><summary><code>client.customer.<a href="/src/api/resources/customer/client/Client.ts">search</a>({ ...params }) -> FiveOneEat.SearchCustomerResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns grouped results for each type. Use per_type to control how many results
appear per section. Optionally filter by category, city, or geo radius.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.search({
    q: "wings",
    categories: "restaurant,bakery",
    city: "Buffalo",
    cuisines: "italian,mexican",
    certifications: "kosher,halal"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.SearchCustomerRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CustomerClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## RecordClick
<details><summary><code>client.recordClick.<a href="/src/api/resources/recordClick/client/Client.ts">adsRecordClick</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.recordClick.adsRecordClick({
    advertisement: "advertisement"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.AdsRecordClickRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `RecordClickClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## ServeAd
<details><summary><code>client.serveAd.<a href="/src/api/resources/serveAd/client/Client.ts">adsServeAd</a>({ ...params }) -> FiveOneEat.AdsServeAdResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.serveAd.adsServeAd({
    placement: "placement"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.AdsServeAdRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ServeAdClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Auth
<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">register</a>({ ...params }) -> FiveOneEat.RegisterAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new business user account and return an API token for immediate authentication.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.register({
    name: "name",
    email: "email",
    password: "password",
    device_name: "device_name",
    password_confirmation: "password_confirmation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.RegisterBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">login</a>({ ...params }) -> FiveOneEat.LoginAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Exchange business user credentials for an API token. Returns a 422 if the account is not a business account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.login({
    email: "email",
    password: "password",
    device_name: "device_name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.LoginBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">forgotPassword</a>({ ...params }) -> FiveOneEat.ForgotPasswordAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sends a password reset link to the provided email address if an account exists.
Always returns a 200 response to prevent email enumeration.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.forgotPassword({
    email: "email"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.ForgotPasswordRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">resetPassword</a>({ ...params }) -> FiveOneEat.ResetPasswordAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Validates the reset token and updates the user's password. All existing API tokens
are revoked after a successful reset, requiring re-authentication on all devices.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.resetPassword({
    token: "token",
    email: "email",
    password: "password",
    password_confirmation: "password_confirmation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.ResetPasswordRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">me</a>() -> FiveOneEat.MeAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve the current authenticated business user with their active business and all owned businesses.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.me();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">logout</a>({ ...params }) -> FiveOneEat.LogoutAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Revoke the current API token and log out the business user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.logout();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.LogoutAuthRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">logoutAll</a>() -> FiveOneEat.LogoutAllAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Revoke all API tokens for the authenticated business user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.logoutAll();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.<a href="/src/api/resources/business/resources/auth/client/Client.ts">switchBusiness</a>({ ...params }) -> FiveOneEat.SwitchBusinessAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Set a different business as the active business for the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.switchBusiness({
    business: "business"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.SwitchBusinessAuthRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Bulletins
<details><summary><code>client.business.bulletins.<a href="/src/api/resources/business/resources/bulletins/client/Client.ts">list</a>() -> FiveOneEat.ListBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.bulletins.<a href="/src/api/resources/business/resources/bulletins/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.create({
    title: "title",
    content: "content",
    type: "post"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreBulletinRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.bulletins.<a href="/src/api/resources/business/resources/bulletins/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.get({
    bulletin: "bulletin"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetBulletinsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.bulletins.<a href="/src/api/resources/business/resources/bulletins/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.update({
    bulletin: "bulletin",
    title: "title",
    content: "content",
    type: "post"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateBulletinRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.bulletins.<a href="/src/api/resources/business/resources/bulletins/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.delete({
    bulletin: "bulletin"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteBulletinsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.bulletins.<a href="/src/api/resources/business/resources/bulletins/client/Client.ts">togglePinned</a>({ ...params }) -> FiveOneEat.TogglePinnedBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.togglePinned({
    bulletin: "bulletin"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.TogglePinnedBulletinsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.bulletins.<a href="/src/api/resources/business/resources/bulletins/client/Client.ts">togglePublished</a>({ ...params }) -> FiveOneEat.TogglePublishedBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.togglePublished({
    bulletin: "bulletin"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.TogglePublishedBulletinsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Businesses
<details><summary><code>client.business.businesses.<a href="/src/api/resources/business/resources/businesses/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a paginated list of all businesses owned by the authenticated user.
Useful for rendering a business picker in the companion mobile app.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.businesses.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.ListBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.businesses.<a href="/src/api/resources/business/resources/businesses/client/Client.ts">create</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new business owned by the authenticated user. The newly created
business is automatically set as the user's active business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.businesses.create({
    name: "name",
    handle: "handle",
    category_ids: [1]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.businesses.<a href="/src/api/resources/business/resources/businesses/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a single business owned by the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.businesses.get({
    business: "business"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.businesses.<a href="/src/api/resources/business/resources/businesses/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update core fields for a business owned by the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.businesses.update({
    business: "business",
    name: "name",
    handle: "handle",
    category_ids: [1]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.businesses.<a href="/src/api/resources/business/resources/businesses/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a business owned by the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.businesses.delete({
    business: "business"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Discounts
<details><summary><code>client.business.discounts.<a href="/src/api/resources/business/resources/discounts/client/Client.ts">list</a>() -> FiveOneEat.ListDiscountsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.discounts.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `DiscountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.discounts.<a href="/src/api/resources/business/resources/discounts/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateDiscountsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.discounts.create({
    code: "code",
    type: "percentage",
    value: 1.1,
    applies_to: "all"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreDiscountRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiscountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.discounts.<a href="/src/api/resources/business/resources/discounts/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetDiscountsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.discounts.get({
    discount: "discount"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetDiscountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiscountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.discounts.<a href="/src/api/resources/business/resources/discounts/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateDiscountsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.discounts.update({
    discount: "discount"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateDiscountRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiscountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.discounts.<a href="/src/api/resources/business/resources/discounts/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteDiscountsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.discounts.delete({
    discount: "discount"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteDiscountsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiscountsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Events
<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">list</a>() -> FiveOneEat.ListEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Accepts an optional `filter` query param: `upcoming`, `past`, or `all` (default `all`).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateEventsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.create({
    title: "title",
    starts_at: "2024-01-15T09:30:00Z",
    ends_at: "2024-01-15T09:30:00Z"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreEventRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetEventsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.get({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateEventsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.update({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateEventRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteEventsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.delete({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">togglePublished</a>({ ...params }) -> FiveOneEat.TogglePublishedEventsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.togglePublished({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.TogglePublishedEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">uploadImage</a>({ ...params }) -> FiveOneEat.UploadImageEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Upload and replace the image for the given event. Any existing image will be deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.uploadImage({
    image: fs.createReadStream("/path/to/your/file"),
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UploadEventImageRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">deleteImage</a>({ ...params }) -> FiveOneEat.DeleteImageEventsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.deleteImage({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteImageEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">listRsvps</a>({ ...params }) -> FiveOneEat.ListRsvpsEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Accepts an optional `status` query param: `attending`, `not_attending`, or `maybe`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.listRsvps({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.ListRsvpsEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">listAttendees</a>({ ...params }) -> FiveOneEat.ListAttendeesEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Accepts an optional `status` query param matching the ticket status
(`valid`, `used`, `cancelled`, `refunded`).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.listAttendees({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.ListAttendeesEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.<a href="/src/api/resources/business/resources/events/client/Client.ts">salesSummary</a>({ ...params }) -> FiveOneEat.SalesSummaryEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns aggregated sales totals: gross revenue, refunds, tickets sold,
and a per-ticket-type breakdown.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.salesSummary({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.SalesSummaryEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Gallery
<details><summary><code>client.business.gallery.<a href="/src/api/resources/business/resources/gallery/client/Client.ts">list</a>() -> FiveOneEat.ListGalleryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.gallery.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `GalleryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.gallery.<a href="/src/api/resources/business/resources/gallery/client/Client.ts">upload</a>({ ...params }) -> FiveOneEat.UploadGalleryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.gallery.upload({
    photo: fs.createReadStream("/path/to/your/file")
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreGalleryPhotoRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GalleryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.gallery.<a href="/src/api/resources/business/resources/gallery/client/Client.ts">reorder</a>({ ...params }) -> FiveOneEat.ReorderGalleryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.gallery.reorder({
    photos: [{
            id: "id",
            sort_order: 1
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.ReorderGalleryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GalleryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.gallery.<a href="/src/api/resources/business/resources/gallery/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateGalleryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.gallery.update({
    photo: "photo"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateGalleryPhotoRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GalleryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.gallery.<a href="/src/api/resources/business/resources/gallery/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteGalleryResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.gallery.delete({
    photo: "photo"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteGalleryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GalleryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Menus
<details><summary><code>client.business.menus.<a href="/src/api/resources/business/resources/menus/client/Client.ts">list</a>() -> FiveOneEat.ListMenusResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns all menus with their full group/item hierarchy for the authenticated user's active business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `MenusClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.<a href="/src/api/resources/business/resources/menus/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateMenusResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.create({
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreMenuRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MenusClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.<a href="/src/api/resources/business/resources/menus/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetMenusResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.get({
    menu: "menu"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetMenusRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MenusClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.<a href="/src/api/resources/business/resources/menus/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateMenusResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.update({
    menu: "menu",
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateMenuRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MenusClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.<a href="/src/api/resources/business/resources/menus/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteMenusResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.delete({
    menu: "menu"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteMenusRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MenusClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Messaging
<details><summary><code>client.business.messaging.<a href="/src/api/resources/business/resources/messaging/client/Client.ts">channelAuth</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

This endpoint is used by the business companion mobile app to authenticate with
Pusher channels. It validates that the authenticated business user has
permission to access the requested channel, scoped to their active business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.messaging.channelAuth({
    channel_name: "channel_name",
    socket_id: "socket_id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.ChannelAuthMessagingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business ProductOrders
<details><summary><code>client.business.productOrders.<a href="/src/api/resources/business/resources/productOrders/client/Client.ts">list</a>() -> FiveOneEat.ListProductOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Accepts optional `status` and `fulfillment_status` query filters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productOrders.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productOrders.<a href="/src/api/resources/business/resources/productOrders/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetProductOrdersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productOrders.get({
    productOrder: "productOrder"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetProductOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productOrders.<a href="/src/api/resources/business/resources/productOrders/client/Client.ts">fulfill</a>({ ...params }) -> FiveOneEat.FulfillProductOrdersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productOrders.fulfill({
    productOrder: "productOrder"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.FulfillProductOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productOrders.<a href="/src/api/resources/business/resources/productOrders/client/Client.ts">markPickedUp</a>({ ...params }) -> FiveOneEat.MarkPickedUpProductOrdersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productOrders.markPickedUp({
    productOrder: "productOrder"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.MarkPickedUpProductOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productOrders.<a href="/src/api/resources/business/resources/productOrders/client/Client.ts">addTracking</a>({ ...params }) -> FiveOneEat.AddTrackingProductOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates a shipment record, marks the order as shipped and fulfilled,
and notifies the customer.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productOrders.addTracking({
    productOrder: "productOrder",
    tracking_number: "tracking_number",
    carrier: "carrier"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreTrackingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productOrders.<a href="/src/api/resources/business/resources/productOrders/client/Client.ts">refund</a>({ ...params }) -> FiveOneEat.RefundProductOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Omit `amount` to issue a full refund.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productOrders.refund({
    productOrder: "productOrder"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.RefundOrderRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Products
<details><summary><code>client.business.products.<a href="/src/api/resources/business/resources/products/client/Client.ts">list</a>() -> FiveOneEat.ListProductsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.<a href="/src/api/resources/business/resources/products/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateProductsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.create({
    name: "name",
    product_type: "physical",
    base_price: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreProductRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.<a href="/src/api/resources/business/resources/products/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetProductsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.get({
    product: "product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetProductsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.<a href="/src/api/resources/business/resources/products/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateProductsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.update({
    product: "product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateProductRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.<a href="/src/api/resources/business/resources/products/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteProductsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.delete({
    product: "product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteProductsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business ProductCategories
<details><summary><code>client.business.productCategories.<a href="/src/api/resources/business/resources/productCategories/client/Client.ts">list</a>() -> FiveOneEat.ListProductCategoriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productCategories.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ProductCategoriesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productCategories.<a href="/src/api/resources/business/resources/productCategories/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateProductCategoriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productCategories.create({
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreProductCategoryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductCategoriesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productCategories.<a href="/src/api/resources/business/resources/productCategories/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateProductCategoriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productCategories.update({
    productCategory: "productCategory"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateProductCategoryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductCategoriesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.productCategories.<a href="/src/api/resources/business/resources/productCategories/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteProductCategoriesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.productCategories.delete({
    productCategory: "productCategory"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteProductCategoriesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductCategoriesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Profile
<details><summary><code>client.business.profile.<a href="/src/api/resources/business/resources/profile/client/Client.ts">get</a>() -> FiveOneEat.GetProfileResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve the full editable profile for the authenticated user's active business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.profile.get();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.profile.<a href="/src/api/resources/business/resources/profile/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateProfileResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update core profile fields for the authenticated user's active business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.profile.update();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateBusinessProfileRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.profile.<a href="/src/api/resources/business/resources/profile/client/Client.ts">syncCuisines</a>({ ...params }) -> FiveOneEat.SyncCuisinesProfileResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replace the set of cuisines associated with the authenticated user's active business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.profile.syncCuisines({
    cuisine_ids: [1]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.SyncCuisinesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.profile.<a href="/src/api/resources/business/resources/profile/client/Client.ts">syncCertifications</a>({ ...params }) -> FiveOneEat.SyncCertificationsProfileResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Replace the set of certifications associated with the authenticated user's active business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.profile.syncCertifications({
    certification_ids: [1]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.SyncCertificationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business PushNotifications
<details><summary><code>client.business.pushNotifications.<a href="/src/api/resources/business/resources/pushNotifications/client/Client.ts">register</a>({ ...params }) -> FiveOneEat.RegisterPushNotificationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Register (or update) the authenticated business user's Expo push token for a
device. If a `device_id` is provided, an existing registration for that device
is updated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.pushNotifications.register({
    token: "token"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StorePushTokenRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PushNotificationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.pushNotifications.<a href="/src/api/resources/business/resources/pushNotifications/client/Client.ts">unregister</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete the authenticated business user's Expo push token registration.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.pushNotifications.unregister({
    token: "token"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UnregisterPushNotificationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PushNotificationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business StripeConnect
<details><summary><code>client.business.stripeConnect.<a href="/src/api/resources/business/resources/stripeConnect/client/Client.ts">status</a>() -> FiveOneEat.StatusStripeConnectResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns the current Stripe Connect connection for the active business,
creating a new Express account on Stripe if one does not yet exist.
Also returns the publishable key and derived flags that the mobile
client uses to decide whether to present onboarding or the management UI.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.stripeConnect.status();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `StripeConnectClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.stripeConnect.<a href="/src/api/resources/business/resources/stripeConnect/client/Client.ts">disconnect</a>() -> FiveOneEat.DisconnectStripeConnectResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Deletes the local StripeConnection record. The Stripe account itself is
not deleted; it becomes orphaned from the business and can be reconnected
later by calling the status endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.stripeConnect.disconnect();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `StripeConnectClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.stripeConnect.<a href="/src/api/resources/business/resources/stripeConnect/client/Client.ts">createAccountSession</a>({ ...params }) -> FiveOneEat.CreateAccountSessionStripeConnectResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

The request body specifies which embedded components to enable on the
session. Use `account_onboarding` during onboarding and any of the
management components (payments, payouts, balances, documents,
account_management, notification_banner, tax_settings, tax_registrations)
after the connected account has submitted their details.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.stripeConnect.createAccountSession({
    components: [{
            enabled: true,
            features: ["features"]
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.CreateAccountSessionRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `StripeConnectClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.stripeConnect.<a href="/src/api/resources/business/resources/stripeConnect/client/Client.ts">refresh</a>() -> FiveOneEat.RefreshStripeConnectResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Pulls the latest account data from Stripe and updates the local
`stripe_connections` record. Provided as a belt-and-suspenders option
alongside the `account.updated` webhook so mobile clients can guarantee
freshness immediately after returning from an onboarding flow.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.stripeConnect.refresh();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `StripeConnectClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Cuisines
<details><summary><code>client.business.cuisines.<a href="/src/api/resources/business/resources/cuisines/client/Client.ts">list</a>() -> FiveOneEat.ListCuisinesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all cuisines, ordered alphabetically. Use these IDs to
populate the `cuisine_ids` field when updating a business profile.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.cuisines.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CuisinesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Certifications
<details><summary><code>client.business.certifications.<a href="/src/api/resources/business/resources/certifications/client/Client.ts">list</a>() -> FiveOneEat.ListCertificationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all certifications, ordered alphabetically. Use these IDs
to populate the `certification_ids` field when updating a business profile.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.certifications.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CertificationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Categories
<details><summary><code>client.business.categories.<a href="/src/api/resources/business/resources/categories/client/Client.ts">list</a>() -> FiveOneEat.ListCategoriesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all business categories, ordered by sort order and name.
Use these IDs to populate the `category_ids` field when creating or updating a business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.categories.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `CategoriesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Allergens
<details><summary><code>client.business.allergens.<a href="/src/api/resources/business/resources/allergens/client/Client.ts">list</a>() -> FiveOneEat.ListAllergensResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all allergens, ordered alphabetically. Use these UUIDs
in the `allergens` array when creating or updating a menu item.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.allergens.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AllergensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business TemporaryLocations
<details><summary><code>client.business.temporaryLocations.<a href="/src/api/resources/business/resources/temporaryLocations/client/Client.ts">list</a>() -> FiveOneEat.ListTemporaryLocationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.temporaryLocations.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `TemporaryLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.temporaryLocations.<a href="/src/api/resources/business/resources/temporaryLocations/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateTemporaryLocationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.temporaryLocations.create({
    title: "title",
    starts_at: "2024-01-15T09:30:00Z",
    ends_at: "2024-01-15T09:30:00Z"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.StoreTemporaryLocationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TemporaryLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.temporaryLocations.<a href="/src/api/resources/business/resources/temporaryLocations/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetTemporaryLocationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.temporaryLocations.get({
    temporaryLocation: "temporaryLocation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.GetTemporaryLocationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TemporaryLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.temporaryLocations.<a href="/src/api/resources/business/resources/temporaryLocations/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateTemporaryLocationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.temporaryLocations.update({
    temporaryLocation: "temporaryLocation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.UpdateTemporaryLocationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TemporaryLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.temporaryLocations.<a href="/src/api/resources/business/resources/temporaryLocations/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteTemporaryLocationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.temporaryLocations.delete({
    temporaryLocation: "temporaryLocation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.DeleteTemporaryLocationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TemporaryLocationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Auth Tokens
<details><summary><code>client.business.auth.tokens.<a href="/src/api/resources/business/resources/auth/resources/tokens/client/Client.ts">list</a>() -> FiveOneEat.ListTokensResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all API tokens for the authenticated business user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.tokens.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.auth.tokens.<a href="/src/api/resources/business/resources/auth/resources/tokens/client/Client.ts">revoke</a>({ ...params }) -> FiveOneEat.RevokeTokensResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a specific API token by its ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.auth.tokens.revoke({
    token: "token"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.auth.RevokeTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Bulletins Comments
<details><summary><code>client.business.bulletins.comments.<a href="/src/api/resources/business/resources/bulletins/resources/comments/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListCommentsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.comments.list({
    bulletin: "bulletin"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.bulletins.ListCommentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CommentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.bulletins.comments.<a href="/src/api/resources/business/resources/bulletins/resources/comments/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateCommentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Omit `parent_id` for a top-level comment. Set `parent_id` to a top-level
comment's id to post a one-level reply (replies to replies are not allowed).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.bulletins.comments.create({
    bulletin: "bulletin",
    body: "body"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.bulletins.StoreBulletinCommentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CommentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Events TicketTypes
<details><summary><code>client.business.events.ticketTypes.<a href="/src/api/resources/business/resources/events/resources/ticketTypes/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListTicketTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.ticketTypes.list({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.ListTicketTypesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketTypesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.ticketTypes.<a href="/src/api/resources/business/resources/events/resources/ticketTypes/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateTicketTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.ticketTypes.create({
    event: "event",
    name: "name",
    price: 1.1,
    quantity_available: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.StoreTicketTypeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketTypesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.ticketTypes.<a href="/src/api/resources/business/resources/events/resources/ticketTypes/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetTicketTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.ticketTypes.get({
    ticketType: "ticketType"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.GetTicketTypesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketTypesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.ticketTypes.<a href="/src/api/resources/business/resources/events/resources/ticketTypes/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateTicketTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.ticketTypes.update({
    ticketType: "ticketType"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.UpdateTicketTypeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketTypesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.ticketTypes.<a href="/src/api/resources/business/resources/events/resources/ticketTypes/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteTicketTypesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.ticketTypes.delete({
    ticketType: "ticketType"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.DeleteTicketTypesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketTypesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Events Orders
<details><summary><code>client.business.events.orders.<a href="/src/api/resources/business/resources/events/resources/orders/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Accepts an optional `status` query param (`pending`, `paid`, `failed`, `refunded`, `partially_refunded`).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.orders.list({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.ListOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.orders.<a href="/src/api/resources/business/resources/events/resources/orders/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetOrdersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.orders.get({
    event: "event",
    order: "order"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.GetOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `OrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Events CheckIn
<details><summary><code>client.business.events.checkIn.<a href="/src/api/resources/business/resources/events/resources/checkIn/client/Client.ts">lookup</a>({ ...params }) -> FiveOneEat.LookupCheckInResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Decodes the base64 QR payload and returns ticket details without performing check-in.
Accepts either a `ticket_id` or `ticket_number` inside the QR payload.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.checkIn.lookup({
    event: "event",
    qr_data: "qr_data"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.LookupTicketRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CheckInClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.checkIn.<a href="/src/api/resources/business/resources/events/resources/checkIn/client/Client.ts">scan</a>({ ...params }) -> FiveOneEat.ScanCheckInResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Decodes the base64 QR payload, validates the ticket's current status, marks it as used,
and broadcasts the `ticket.checked-in` event via Reverb.

Returns `409` if the ticket has already been checked in, `400` for refunded or otherwise
invalid tickets.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.checkIn.scan({
    event: "event",
    qr_data: "qr_data"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.ScanTicketRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CheckInClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.checkIn.<a href="/src/api/resources/business/resources/events/resources/checkIn/client/Client.ts">stats</a>({ ...params }) -> FiveOneEat.StatsCheckInResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns ticket counts and check-in rate for the event dashboard.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.checkIn.stats({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.StatsCheckInRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CheckInClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.events.checkIn.<a href="/src/api/resources/business/resources/events/resources/checkIn/client/Client.ts">recent</a>({ ...params }) -> FiveOneEat.RecentCheckInResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns checked-in tickets ordered by check-in time descending.
Accepts an optional `limit` query param (default `20`, max `100`).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.events.checkIn.recent({
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.events.RecentCheckInRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CheckInClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Menus Groups
<details><summary><code>client.business.menus.groups.<a href="/src/api/resources/business/resources/menus/resources/groups/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListGroupsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.groups.list({
    menu: "menu"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.ListGroupsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GroupsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.groups.<a href="/src/api/resources/business/resources/menus/resources/groups/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateGroupsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.groups.create({
    menu: "menu",
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.StoreMenuGroupRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GroupsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.groups.<a href="/src/api/resources/business/resources/menus/resources/groups/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetGroupsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.groups.get({
    menu: "menu",
    group: "group"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.GetGroupsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GroupsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.groups.<a href="/src/api/resources/business/resources/menus/resources/groups/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateGroupsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.groups.update({
    menu: "menu",
    group: "group",
    name: "name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.UpdateMenuGroupRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GroupsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.groups.<a href="/src/api/resources/business/resources/menus/resources/groups/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteGroupsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.groups.delete({
    menu: "menu",
    group: "group"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.DeleteGroupsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GroupsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.groups.<a href="/src/api/resources/business/resources/menus/resources/groups/client/Client.ts">reorder</a>({ ...params }) -> FiveOneEat.ReorderGroupsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Batch-update sort_order for groups. Groups not belonging to this menu are silently skipped.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.groups.reorder({
    menu: "menu",
    groups: [{
            id: "id",
            sort_order: 1
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.ReorderGroupsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `GroupsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Menus Items
<details><summary><code>client.business.menus.items.<a href="/src/api/resources/business/resources/menus/resources/items/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.list({
    menu: "menu"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.ListItemsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.<a href="/src/api/resources/business/resources/menus/resources/items/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.create({
    menu: "menu",
    name: "name",
    price: 1.1,
    menu_group_id: "menu_group_id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.StoreMenuItemRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.<a href="/src/api/resources/business/resources/menus/resources/items/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.get({
    menu: "menu",
    item: "item"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.GetItemsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.<a href="/src/api/resources/business/resources/menus/resources/items/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.update({
    menu: "menu",
    item: "item",
    name: "name",
    price: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.UpdateMenuItemRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.<a href="/src/api/resources/business/resources/menus/resources/items/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.delete({
    menu: "menu",
    item: "item"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.DeleteItemsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.<a href="/src/api/resources/business/resources/menus/resources/items/client/Client.ts">reorder</a>({ ...params }) -> FiveOneEat.ReorderItemsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Batch-update sort_order for items. Items not belonging to this group are silently skipped.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.reorder({
    group: "group",
    items: [{
            id: "id",
            sort_order: 1
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.ReorderItemsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.<a href="/src/api/resources/business/resources/menus/resources/items/client/Client.ts">move</a>({ ...params }) -> FiveOneEat.MoveItemsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Moves the item to the target group at the specified sort order, shifting existing items to make room.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.move({
    item: "item",
    target_group_id: "target_group_id",
    new_sort_order: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.MoveItemsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ItemsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Menus Items Variations
<details><summary><code>client.business.menus.items.variations.<a href="/src/api/resources/business/resources/menus/resources/items/resources/variations/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListVariationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.variations.list({
    menuItem: "menuItem"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.items.ListVariationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VariationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.variations.<a href="/src/api/resources/business/resources/menus/resources/items/resources/variations/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateVariationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.variations.create({
    menuItem: "menuItem",
    name: "name",
    price: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.items.StoreMenuItemVariationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VariationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.variations.<a href="/src/api/resources/business/resources/menus/resources/items/resources/variations/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateVariationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.variations.update({
    variation: "variation",
    name: "name",
    price: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.items.UpdateMenuItemVariationRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VariationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.variations.<a href="/src/api/resources/business/resources/menus/resources/items/resources/variations/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteVariationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.variations.delete({
    variation: "variation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.items.DeleteVariationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VariationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Menus Items Modifiers
<details><summary><code>client.business.menus.items.modifiers.<a href="/src/api/resources/business/resources/menus/resources/items/resources/modifiers/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListModifiersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.modifiers.list({
    menuItem: "menuItem"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.items.ListModifiersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ModifiersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.modifiers.<a href="/src/api/resources/business/resources/menus/resources/items/resources/modifiers/client/Client.ts">attach</a>({ ...params }) -> FiveOneEat.AttachModifiersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Creates the modifier if it does not already exist (matched by name), then attaches it to the item.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.modifiers.attach({
    menuItem: "menuItem",
    name: "name",
    price: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.items.StoreMenuItemModifierRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ModifiersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.menus.items.modifiers.<a href="/src/api/resources/business/resources/menus/resources/items/resources/modifiers/client/Client.ts">detach</a>({ ...params }) -> FiveOneEat.DetachModifiersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes the association between the modifier and the item. The modifier itself is not deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.menus.items.modifiers.detach({
    menuItem: "menuItem",
    modifier: "modifier"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.menus.items.DetachModifiersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ModifiersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Messaging Conversations
<details><summary><code>client.business.messaging.conversations.<a href="/src/api/resources/business/resources/messaging/resources/conversations/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListConversationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a paginated list of all conversations for the authenticated business,
ordered by the most recent message first.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.messaging.conversations.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.messaging.ListConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ConversationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.messaging.conversations.<a href="/src/api/resources/business/resources/messaging/resources/conversations/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetConversationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve details of a specific conversation including the customer information
and the latest message.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.messaging.conversations.get({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.messaging.GetConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ConversationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Messaging Messages
<details><summary><code>client.business.messaging.messages.<a href="/src/api/resources/business/resources/messaging/resources/messages/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListMessagesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a paginated list of all messages in a specific conversation,
ordered by creation time (oldest first).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.messaging.messages.list({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.messaging.ListMessagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.messaging.messages.<a href="/src/api/resources/business/resources/messaging/resources/messages/client/Client.ts">send</a>({ ...params }) -> FiveOneEat.SendMessagesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Send a new message to a specific conversation as the business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.messaging.messages.send({
    conversation: "550e8400-e29b-41d4-a716-446655440000",
    content: "content"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.messaging.StoreMessageRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.messaging.messages.<a href="/src/api/resources/business/resources/messaging/resources/messages/client/Client.ts">markAsRead</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Mark all messages from the customer as read by the business user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.messaging.messages.markAsRead({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.messaging.MarkAsReadMessagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.messaging.messages.<a href="/src/api/resources/business/resources/messaging/resources/messages/client/Client.ts">unreadCount</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the count of unread messages from the customer in a specific conversation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.messaging.messages.unreadCount({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.messaging.UnreadCountMessagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Products Variants
<details><summary><code>client.business.products.variants.<a href="/src/api/resources/business/resources/products/resources/variants/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateVariantsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.variants.create({
    product: "product",
    name: "name",
    price: 1.1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.StoreProductVariantRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VariantsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.variants.<a href="/src/api/resources/business/resources/products/resources/variants/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateVariantsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.variants.update({
    variant: "variant"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.UpdateProductVariantRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VariantsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.variants.<a href="/src/api/resources/business/resources/products/resources/variants/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteVariantsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.variants.delete({
    variant: "variant"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.DeleteVariantsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `VariantsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Products Images
<details><summary><code>client.business.products.images.<a href="/src/api/resources/business/resources/products/resources/images/client/Client.ts">upload</a>({ ...params }) -> FiveOneEat.UploadImagesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.images.upload({
    image: fs.createReadStream("/path/to/your/file"),
    product: "product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.UploadImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.images.<a href="/src/api/resources/business/resources/products/resources/images/client/Client.ts">reorder</a>({ ...params }) -> FiveOneEat.ReorderImagesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.images.reorder({
    product: "product",
    body: {
        images: [{
                id: "id",
                sort_order: 1
            }]
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.ReorderImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.images.<a href="/src/api/resources/business/resources/products/resources/images/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteImagesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.images.delete({
    product: "product",
    image: "image"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.DeleteImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Products Variants Images
<details><summary><code>client.business.products.variants.images.<a href="/src/api/resources/business/resources/products/resources/variants/resources/images/client/Client.ts">upload</a>({ ...params }) -> FiveOneEat.UploadImagesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.variants.images.upload({
    image: fs.createReadStream("/path/to/your/file"),
    variant: "variant"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.variants.UploadImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.variants.images.<a href="/src/api/resources/business/resources/products/resources/variants/resources/images/client/Client.ts">reorder</a>({ ...params }) -> FiveOneEat.ReorderImagesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.variants.images.reorder({
    variant: "variant",
    body: {
        images: [{
                id: "id",
                sort_order: 1
            }]
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.variants.ReorderImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.products.variants.images.<a href="/src/api/resources/business/resources/products/resources/variants/resources/images/client/Client.ts">delete</a>({ ...params }) -> FiveOneEat.DeleteImagesResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.products.variants.images.delete({
    variant: "variant",
    image: "image"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.products.variants.DeleteImagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ImagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Profile Logo
<details><summary><code>client.business.profile.logo.<a href="/src/api/resources/business/resources/profile/resources/logo/client/Client.ts">upload</a>({ ...params }) -> FiveOneEat.UploadLogoResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Upload and replace the logo for the authenticated user's active business. Any existing logo file will be deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.profile.logo.upload({
    logo: fs.createReadStream("/path/to/your/file")
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.business.profile.UploadLogoRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `LogoClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.business.profile.logo.<a href="/src/api/resources/business/resources/profile/resources/logo/client/Client.ts">delete</a>() -> FiveOneEat.DeleteLogoResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Remove the logo for the authenticated user's active business, including the stored file.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.business.profile.logo.delete();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `LogoClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Auth
<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">register</a>({ ...params }) -> FiveOneEat.RegisterAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new customer account and return an API token for immediate authentication.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.register({
    name: "name",
    email: "email",
    password: "password",
    device_name: "device_name",
    password_confirmation: "password_confirmation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.RegisterCustomerRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">login</a>({ ...params }) -> FiveOneEat.LoginAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Exchange user credentials for an API token that can be used for subsequent authenticated requests.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.login({
    email: "email",
    password: "password",
    device_name: "device_name"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.LoginCustomerRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">forgotPassword</a>({ ...params }) -> FiveOneEat.ForgotPasswordAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Sends a password reset link to the provided email address if an account exists.
Always returns a 200 response to prevent email enumeration.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.forgotPassword({
    email: "email"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.AppHttpRequestsApiV1CustomerAuthForgotPasswordRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">resetPassword</a>({ ...params }) -> FiveOneEat.ResetPasswordAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Validates the reset token and updates the user's password. All existing API tokens
are revoked after a successful reset, requiring re-authentication on all devices.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.resetPassword({
    token: "token",
    email: "email",
    password: "password",
    password_confirmation: "password_confirmation"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.AppHttpRequestsApiV1CustomerAuthResetPasswordRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">me</a>() -> FiveOneEat.MeAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve the current authenticated user's profile information.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.me();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">updateProfile</a>({ ...params }) -> FiveOneEat.UpdateProfileAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update name, email, and/or password. All fields are optional. To change the
password, `current_password` must be provided alongside `password` and `password_confirmation`.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.updateProfile();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.UpdateUserRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">uploadAvatar</a>({ ...params }) -> FiveOneEat.UploadAvatarAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Upload and replace the avatar for the authenticated customer. Any existing avatar file will be deleted.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.uploadAvatar({
    avatar: "avatar"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.UploadAvatarRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">deleteAvatar</a>() -> FiveOneEat.DeleteAvatarAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Remove the avatar for the authenticated customer. Returns the updated user with a null avatar_url.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.deleteAvatar();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">logout</a>({ ...params }) -> FiveOneEat.LogoutAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Revoke the current API token and log out the user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.logout();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.LogoutAuthRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.<a href="/src/api/resources/customer/resources/auth/client/Client.ts">logoutAll</a>() -> FiveOneEat.LogoutAllAuthResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Revoke all API tokens for the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.logoutAll();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AuthClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Businesses
<details><summary><code>client.customer.businesses.<a href="/src/api/resources/customer/resources/businesses/client/Client.ts">profile</a>({ ...params }) -> FiveOneEat.ProfileBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve core business information for the profile page.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.profile({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.ProfileBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.<a href="/src/api/resources/customer/resources/businesses/client/Client.ts">menus</a>({ ...params }) -> FiveOneEat.MenusBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve all menus organized by groups for the business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.menus({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.MenusBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.<a href="/src/api/resources/customer/resources/businesses/client/Client.ts">photos</a>({ ...params }) -> FiveOneEat.PhotosBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve photo gallery for the business with pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.photos({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.PhotosBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.<a href="/src/api/resources/customer/resources/businesses/client/Client.ts">favorite</a>({ ...params }) -> FiveOneEat.FavoriteBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Add a business to the authenticated user's favorites.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.favorite({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.FavoriteBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.<a href="/src/api/resources/customer/resources/businesses/client/Client.ts">unfavorite</a>({ ...params }) -> Record&lt;string, unknown&gt;</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Remove a business from the authenticated user's favorites.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.unfavorite({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.UnfavoriteBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.<a href="/src/api/resources/customer/resources/businesses/client/Client.ts">listTemporaryLocations</a>({ ...params }) -> FiveOneEat.ListTemporaryLocationsBusinessesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve active and upcoming temporary locations for a business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.listTemporaryLocations({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.ListTemporaryLocationsBusinessesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Cart
<details><summary><code>client.customer.cart.<a href="/src/api/resources/customer/resources/cart/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetCartResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.cart.get({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.GetCartRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CartClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.cart.<a href="/src/api/resources/customer/resources/cart/client/Client.ts">addItem</a>({ ...params }) -> FiveOneEat.AddItemCartResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.cart.addItem({
    business: "katzs-deli",
    product_id: 1,
    quantity: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.AddToCartRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CartClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.cart.<a href="/src/api/resources/customer/resources/cart/client/Client.ts">clear</a>({ ...params }) -> FiveOneEat.ClearCartResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.cart.clear({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.ClearCartRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CartClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.cart.<a href="/src/api/resources/customer/resources/cart/client/Client.ts">createPaymentIntent</a>({ ...params }) -> FiveOneEat.CreatePaymentIntentCartResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns client_secret, price breakdown, and tax calculation for use with Stripe SDK.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.cart.createPaymentIntent({
    business: "katzs-deli",
    billing_address: {
        line1: "line1",
        city: "city",
        state: "state",
        postal_code: "postal_code",
        country: "country"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.CreatePaymentIntentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CartClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.cart.<a href="/src/api/resources/customer/resources/cart/client/Client.ts">checkout</a>({ ...params }) -> FiveOneEat.CheckoutCartResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Verifies the Stripe payment intent, creates the order, decrements inventory,
clears the cart, and dispatches order confirmation notifications.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.cart.checkout({
    business: "katzs-deli",
    payment_intent_id: "payment_intent_id",
    billing_address: {
        line1: "line1",
        city: "city",
        state: "state",
        postal_code: "postal_code",
        country: "country"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.CheckoutRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CartClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.cart.<a href="/src/api/resources/customer/resources/cart/client/Client.ts">updateItem</a>({ ...params }) -> FiveOneEat.UpdateItemCartResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.cart.updateItem({
    cartItem: "cartItem",
    quantity: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.UpdateCartItemRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CartClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.cart.<a href="/src/api/resources/customer/resources/cart/client/Client.ts">removeItem</a>({ ...params }) -> FiveOneEat.RemoveItemCartResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.cart.removeItem({
    cartItem: "cartItem"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.RemoveItemCartRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CartClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Explore
<details><summary><code>client.customer.explore.<a href="/src/api/resources/customer/resources/explore/client/Client.ts">businesses</a>({ ...params }) -> FiveOneEat.BusinessesExploreResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve businesses within the specified map bounds for map view.
Results are optimized for map display with essential business information.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.explore.businesses({
    bounds: "43.5000,42.5000,-73.5000,-76.5000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.BusinessesExploreRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ExploreClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Discovery
<details><summary><code>client.customer.discovery.<a href="/src/api/resources/customer/resources/discovery/client/Client.ts">feed</a>({ ...params }) -> FiveOneEat.DiscoveryFeed</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a paginated list of populated business categories, each with up to 10 businesses
embedded. Use `total_businesses` to link to the full paginated category view.
Supports optional filtering by search term, cuisines, and certifications.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.discovery.feed({
    search: "organic"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.FeedDiscoveryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiscoveryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.discovery.<a href="/src/api/resources/customer/resources/discovery/client/Client.ts">highlights</a>() -> FiveOneEat.DiscoveryHighlights</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns curated sections of businesses for the discovery home screen,
including staff picks and founding partners. This endpoint is designed
to be extended with additional sections (e.g. editorial, trending) over time.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.discovery.highlights();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `DiscoveryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.discovery.<a href="/src/api/resources/customer/resources/discovery/client/Client.ts">categories</a>({ ...params }) -> FiveOneEat.CategoriesDiscoveryResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all business categories with their business counts.
This endpoint is used to populate category filters and navigation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.discovery.categories();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.CategoriesDiscoveryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiscoveryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.discovery.<a href="/src/api/resources/customer/resources/discovery/client/Client.ts">cuisines</a>() -> FiveOneEat.CuisinesDiscoveryResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all cuisines, ordered alphabetically.
This endpoint is used to populate cuisine filters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.discovery.cuisines();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `DiscoveryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.discovery.<a href="/src/api/resources/customer/resources/discovery/client/Client.ts">certifications</a>() -> FiveOneEat.CertificationsDiscoveryResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all certifications, ordered alphabetically.
This endpoint is used to populate certification filters.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.discovery.certifications();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `DiscoveryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.discovery.<a href="/src/api/resources/customer/resources/discovery/client/Client.ts">allergens</a>() -> FiveOneEat.AllergensDiscoveryResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all allergens, ordered alphabetically, for use in
filters, labels, and other customer-facing display.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.discovery.allergens();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `DiscoveryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.discovery.<a href="/src/api/resources/customer/resources/discovery/client/Client.ts">categoryBusinesses</a>({ ...params }) -> FiveOneEat.CategoryBusinessesDiscoveryResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve businesses for a specific category with pagination support.
Results are optimized for list display.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.discovery.categoryBusinesses({
    category: "restaurant",
    search: "coffee"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.CategoryBusinessesDiscoveryRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `DiscoveryClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Editorials
<details><summary><code>client.customer.editorials.<a href="/src/api/resources/customer/resources/editorials/client/Client.ts">list</a>() -> FiveOneEat.ListEditorialsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a paginated list of published editorials with basic business info.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.editorials.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `EditorialsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.editorials.<a href="/src/api/resources/customer/resources/editorials/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetEditorialsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a published editorial by slug, with the full augmented body
including resolved menu item, product, and event references.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.editorials.get({
    slug: "slug"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.GetEditorialsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EditorialsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Events
<details><summary><code>client.customer.events.<a href="/src/api/resources/customer/resources/events/client/Client.ts">feed</a>({ ...params }) -> FiveOneEat.FeedEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a paginated feed of upcoming events across all businesses.
Defaults to all events starting from now, ordered by start date ascending.
Optionally filter by a date range using date_from and date_to.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.events.feed({
    date_from: "2026-05-01",
    date_to: "2026-05-31"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.FeedEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Messaging
<details><summary><code>client.customer.messaging.<a href="/src/api/resources/customer/resources/messaging/client/Client.ts">channelAuth</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

This endpoint is used by the mobile app to authenticate with Pusher channels.
It validates that the user has permission to access the requested channel.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.channelAuth({
    channel_name: "channel_name",
    socket_id: "socket_id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.ChannelAuthMessagingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Me
<details><summary><code>client.customer.me.<a href="/src/api/resources/customer/resources/me/client/Client.ts">favorites</a>({ ...params }) -> FiveOneEat.FavoritesMeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve the authenticated user's favorited businesses with pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.favorites();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.FavoritesMeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MeClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.<a href="/src/api/resources/customer/resources/me/client/Client.ts">rsvps</a>({ ...params }) -> FiveOneEat.RsvpsMeResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve the authenticated user's event RSVPs with pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.rsvps({
    status: "attending"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.RsvpsMeRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MeClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer ProductOrders
<details><summary><code>client.customer.productOrders.<a href="/src/api/resources/customer/resources/productOrders/client/Client.ts">list</a>() -> FiveOneEat.ListProductOrdersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.productOrders.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.productOrders.<a href="/src/api/resources/customer/resources/productOrders/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetProductOrdersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.productOrders.get({
    productOrder: "productOrder"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.GetProductOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ProductOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer PushNotifications
<details><summary><code>client.customer.pushNotifications.<a href="/src/api/resources/customer/resources/pushNotifications/client/Client.ts">register</a>({ ...params }) -> FiveOneEat.RegisterPushNotificationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Register (or update) the authenticated user's Expo push token for a device. If
a `device_id` is provided, an existing registration for that device is updated.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.pushNotifications.register({
    token: "token"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.AppHttpRequestsApiV1CustomerPushTokensStorePushTokenRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PushNotificationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.pushNotifications.<a href="/src/api/resources/customer/resources/pushNotifications/client/Client.ts">unregister</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete the authenticated user's Expo push token registration.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.pushNotifications.unregister({
    token: "token"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.UnregisterPushNotificationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PushNotificationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Shop
<details><summary><code>client.customer.shop.<a href="/src/api/resources/customer/resources/shop/client/Client.ts">listProducts</a>({ ...params }) -> FiveOneEat.ListProductsShopResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.shop.listProducts({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.ListProductsShopRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ShopClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.shop.<a href="/src/api/resources/customer/resources/shop/client/Client.ts">getProduct</a>({ ...params }) -> FiveOneEat.GetProductShopResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.shop.getProduct({
    business: "katzs-deli",
    product: "product"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.GetProductShopRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ShopClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.shop.<a href="/src/api/resources/customer/resources/shop/client/Client.ts">listCategories</a>({ ...params }) -> FiveOneEat.ListCategoriesShopResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.shop.listCategories({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.ListCategoriesShopRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ShopClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Auth Tokens
<details><summary><code>client.customer.auth.tokens.<a href="/src/api/resources/customer/resources/auth/resources/tokens/client/Client.ts">list</a>() -> FiveOneEat.ListTokensResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all API tokens for the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.tokens.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.auth.tokens.<a href="/src/api/resources/customer/resources/auth/resources/tokens/client/Client.ts">revoke</a>({ ...params }) -> FiveOneEat.RevokeTokensResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a specific API token by its ID.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.auth.tokens.revoke({
    token: "token"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.auth.RevokeTokensRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TokensClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Businesses Bulletins
<details><summary><code>client.customer.businesses.bulletins.<a href="/src/api/resources/customer/resources/businesses/resources/bulletins/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListBulletinsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve business announcements and updates with pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.bulletins.list({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.ListBulletinsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BulletinsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Businesses Events
<details><summary><code>client.customer.businesses.events.<a href="/src/api/resources/customer/resources/businesses/resources/events/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve upcoming events for the business with pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.events.list({
    business: "katzs-deli"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.ListEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.events.<a href="/src/api/resources/customer/resources/businesses/resources/events/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve full details for a single upcoming event belonging to the business.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.events.get({
    business: "katzs-deli",
    event: "event"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.GetEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.events.<a href="/src/api/resources/customer/resources/businesses/resources/events/client/Client.ts">rsvp</a>({ ...params }) -> FiveOneEat.RsvpEventsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create or update the authenticated user's RSVP for a business event.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.events.rsvp({
    business: "katzs-deli",
    event: "01950e7d-1234-7000-abcd-ef0123456789",
    status: "attending"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.StoreEventRsvpRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.events.<a href="/src/api/resources/customer/resources/businesses/resources/events/client/Client.ts">cancelRsvp</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Cancel the authenticated user's RSVP for a business event.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.events.cancelRsvp({
    business: "katzs-deli",
    event: "01950e7d-1234-7000-abcd-ef0123456789"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.CancelRsvpEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `EventsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Businesses Bulletins Comments
<details><summary><code>client.customer.businesses.bulletins.comments.<a href="/src/api/resources/customer/resources/businesses/resources/bulletins/resources/comments/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListCommentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve paginated comments for a published business bulletin.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.bulletins.comments.list({
    business: "katzs-deli",
    bulletin: "01950e7d-1234-7000-abcd-ef0123456789"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.bulletins.ListCommentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CommentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.bulletins.comments.<a href="/src/api/resources/customer/resources/businesses/resources/bulletins/resources/comments/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateCommentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Post a comment on a business bulletin. Requires authentication.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.bulletins.comments.create({
    business: "katzs-deli",
    bulletin: "01950e7d-1234-7000-abcd-ef0123456789",
    body: "body"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.bulletins.AppHttpRequestsApiV1CustomerBusinessesStoreBulletinCommentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CommentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.bulletins.comments.<a href="/src/api/resources/customer/resources/businesses/resources/bulletins/resources/comments/client/Client.ts">listReplies</a>({ ...params }) -> FiveOneEat.ListRepliesCommentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve paginated replies for a top-level comment on a published bulletin.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.bulletins.comments.listReplies({
    business: "katzs-deli",
    bulletin: "01950e7d-1234-7000-abcd-ef0123456789",
    comment: "01950e7d-5678-7000-abcd-ef0123456789"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.bulletins.ListRepliesCommentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CommentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.businesses.bulletins.comments.<a href="/src/api/resources/customer/resources/businesses/resources/bulletins/resources/comments/client/Client.ts">reply</a>({ ...params }) -> FiveOneEat.ReplyCommentsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Post a reply to a top-level comment on a published bulletin. Requires authentication.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.businesses.bulletins.comments.reply({
    business: "katzs-deli",
    bulletin: "01950e7d-1234-7000-abcd-ef0123456789",
    comment: "01950e7d-5678-7000-abcd-ef0123456789",
    body: "body"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.businesses.bulletins.StoreBulletinCommentReplyRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `CommentsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Events Ticketing
<details><summary><code>client.customer.events.ticketing.<a href="/src/api/resources/customer/resources/events/resources/ticketing/client/Client.ts">holdTickets</a>({ ...params }) -> FiveOneEat.HoldTicketsTicketingResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Place a temporary hold on tickets for the specified event. Holds expire after 10 minutes.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.events.ticketing.holdTickets({
    eventId: "eventId",
    tickets: [{
            ticket_type_id: "ticket_type_id",
            quantity: 1
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.events.StoreTicketHoldRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.events.ticketing.<a href="/src/api/resources/customer/resources/events/resources/ticketing/client/Client.ts">calculatePrice</a>({ ...params }) -> FiveOneEat.CalculatePriceTicketingResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Preview the subtotal, platform fee, and total for a given ticket selection.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.events.ticketing.calculatePrice({
    eventId: "eventId",
    tickets: [{
            ticket_type_id: "ticket_type_id",
            quantity: 1
        }]
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.events.CalculatePriceRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.events.ticketing.<a href="/src/api/resources/customer/resources/events/resources/ticketing/client/Client.ts">createPaymentIntent</a>({ ...params }) -> FiveOneEat.CreatePaymentIntentTicketingResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a Stripe payment intent for the tickets held in the cart for the given event.
Returns a client_secret for the mobile app to confirm payment with Stripe.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.events.ticketing.createPaymentIntent({
    eventId: "eventId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.events.AppHttpRequestsApiV1CustomerEventsCreatePaymentIntentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.events.ticketing.<a href="/src/api/resources/customer/resources/events/resources/ticketing/client/Client.ts">confirmOrder</a>({ ...params }) -> FiveOneEat.ConfirmOrderTicketingResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Confirm a completed Stripe payment and create the ticket order.
The payment must have succeeded before calling this endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.events.ticketing.confirmOrder({
    eventId: "eventId",
    payment_intent_id: "payment_intent_id"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.events.StoreTicketOrderRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.events.ticketing.<a href="/src/api/resources/customer/resources/events/resources/ticketing/client/Client.ts">releaseHold</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.events.ticketing.releaseHold({
    eventId: "eventId",
    sessionId: "sessionId"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.events.ReleaseHoldTicketingRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Me Tickets
<details><summary><code>client.customer.me.tickets.<a href="/src/api/resources/customer/resources/me/resources/tickets/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListTicketsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve the authenticated user's tickets with pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.tickets.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.ListTicketsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.tickets.<a href="/src/api/resources/customer/resources/me/resources/tickets/client/Client.ts">get</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.tickets.get({
    ticket: "ticket"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.GetTicketsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Me TicketOrders
<details><summary><code>client.customer.me.ticketOrders.<a href="/src/api/resources/customer/resources/me/resources/ticketOrders/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListTicketOrdersResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve the authenticated user's ticket orders with pagination.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.ticketOrders.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.ListTicketOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.ticketOrders.<a href="/src/api/resources/customer/resources/me/resources/ticketOrders/client/Client.ts">get</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.ticketOrders.get({
    order: "order"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.GetTicketOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `TicketOrdersClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Me Addresses
<details><summary><code>client.customer.me.addresses.<a href="/src/api/resources/customer/resources/me/resources/addresses/client/Client.ts">list</a>() -> FiveOneEat.ListAddressesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve all saved addresses for the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.addresses.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `AddressesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.addresses.<a href="/src/api/resources/customer/resources/me/resources/addresses/client/Client.ts">create</a>({ ...params }) -> FiveOneEat.CreateAddressesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Save a new address to the authenticated user's account. If this is the first address,
or if `is_default` is true, it will be set as the default (clearing any existing default).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.addresses.create({
    line1: "line1",
    city: "city",
    state: "state",
    postal_code: "postal_code",
    country: "country"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.StoreAddressRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AddressesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.addresses.<a href="/src/api/resources/customer/resources/me/resources/addresses/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Delete a saved address. If the deleted address was the default,
the most recently created remaining address is promoted to default.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.addresses.delete({
    address: 1
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.DeleteAddressesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AddressesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.addresses.<a href="/src/api/resources/customer/resources/me/resources/addresses/client/Client.ts">update</a>({ ...params }) -> FiveOneEat.UpdateAddressesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Update a saved address. If `is_default` is true, the previous default address will be cleared.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.addresses.update({
    address: 1,
    body: {
        line1: "line1",
        city: "city",
        state: "state",
        postal_code: "postal_code",
        country: "country"
    }
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.UpdateAddressesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AddressesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Me PaymentMethods
<details><summary><code>client.customer.me.paymentMethods.<a href="/src/api/resources/customer/resources/me/resources/paymentMethods/client/Client.ts">setupIntent</a>() -> FiveOneEat.SetupIntentPaymentMethodsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns a Stripe SetupIntent client_secret. Use this with the Stripe mobile SDK
to present the payment sheet and collect card details. Once confirmed, pass the
resulting payment method ID to the store endpoint.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.paymentMethods.setupIntent();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `PaymentMethodsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.paymentMethods.<a href="/src/api/resources/customer/resources/me/resources/paymentMethods/client/Client.ts">list</a>() -> FiveOneEat.PaymentMethod[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Returns all saved cards for the authenticated user.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.paymentMethods.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `PaymentMethodsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.paymentMethods.<a href="/src/api/resources/customer/resources/me/resources/paymentMethods/client/Client.ts">add</a>({ ...params }) -> FiveOneEat.AddPaymentMethodsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Attaches a confirmed payment method to the customer's account. If `is_default` is
true, or this is the first card saved, it becomes the default payment method.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.paymentMethods.add({
    payment_method: "payment_method"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.StorePaymentMethodRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaymentMethodsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.paymentMethods.<a href="/src/api/resources/customer/resources/me/resources/paymentMethods/client/Client.ts">setDefault</a>({ ...params }) -> FiveOneEat.SetDefaultPaymentMethodsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Marks an existing saved payment method as the default.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.paymentMethods.setDefault({
    paymentMethod: "paymentMethod"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.SetDefaultPaymentMethodsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaymentMethodsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.me.paymentMethods.<a href="/src/api/resources/customer/resources/me/resources/paymentMethods/client/Client.ts">delete</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Removes a saved payment method from the customer's account.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.me.paymentMethods.delete({
    paymentMethod: "paymentMethod"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.me.DeletePaymentMethodsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `PaymentMethodsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Messaging Conversations
<details><summary><code>client.customer.messaging.conversations.<a href="/src/api/resources/customer/resources/messaging/resources/conversations/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListConversationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a paginated list of all conversations for the authenticated customer,
ordered by the most recent message first.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.conversations.list();

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.ListConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ConversationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.messaging.conversations.<a href="/src/api/resources/customer/resources/messaging/resources/conversations/client/Client.ts">start</a>({ ...params }) -> FiveOneEat.StartConversationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a new conversation between the authenticated customer and the specified business.
If a conversation already exists, it will be returned instead of creating a duplicate.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.conversations.start({
    business: "marios-pizza"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.StartConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ConversationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.messaging.conversations.<a href="/src/api/resources/customer/resources/messaging/resources/conversations/client/Client.ts">get</a>({ ...params }) -> FiveOneEat.GetConversationsResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve details of a specific conversation including the business information
and the latest message.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.conversations.get({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.GetConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ConversationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.messaging.conversations.<a href="/src/api/resources/customer/resources/messaging/resources/conversations/client/Client.ts">delete</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Permanently delete a conversation and all its messages.
This action cannot be undone.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.conversations.delete({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.DeleteConversationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `ConversationsClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Messaging Messages
<details><summary><code>client.customer.messaging.messages.<a href="/src/api/resources/customer/resources/messaging/resources/messages/client/Client.ts">list</a>({ ...params }) -> FiveOneEat.ListMessagesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a paginated list of all messages in a specific conversation,
ordered by creation time (oldest first).
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.messages.list({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.ListMessagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.messaging.messages.<a href="/src/api/resources/customer/resources/messaging/resources/messages/client/Client.ts">send</a>({ ...params }) -> FiveOneEat.SendMessagesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Send a new message to a specific conversation. The message will be marked
as sent by the authenticated customer.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.messages.send({
    conversation: "550e8400-e29b-41d4-a716-446655440000",
    content: "Hello! I have a question about your menu."
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.SendMessagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.messaging.messages.<a href="/src/api/resources/customer/resources/messaging/resources/messages/client/Client.ts">markAsRead</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Mark all messages in a conversation as read by the authenticated customer.
This is typically called when the customer opens a conversation.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.messages.markAsRead({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.MarkAsReadMessagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.customer.messaging.messages.<a href="/src/api/resources/customer/resources/messaging/resources/messages/client/Client.ts">unreadCount</a>({ ...params }) -> number</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Get the count of unread messages in a specific conversation for the authenticated customer.
</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.customer.messaging.messages.unreadCount({
    conversation: "550e8400-e29b-41d4-a716-446655440000"
});

```
</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `FiveOneEat.customer.messaging.UnreadCountMessagesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MessagesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

