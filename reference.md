# Reference
<details><summary><code>client.<a href="/src/Client.ts">search</a>({ ...params }) -> FiveOneEat.SearchResponse</code></summary>
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
await client.search({
    q: "wings",
    category: "restaurant",
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

**request:** `FiveOneEat.SearchRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `FiveOneEatClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Authentication
<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">registerCustomer</a>({ ...params }) -> FiveOneEat.RegisterCustomerResponse</code></summary>
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
await client.authentication.registerCustomer({
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

**request:** `FiveOneEat.RegisterCustomerRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">loginCustomer</a>({ ...params }) -> FiveOneEat.LoginCustomerResponse</code></summary>
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
await client.authentication.loginCustomer({
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

**request:** `FiveOneEat.LoginCustomerRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">getCurrentUser</a>() -> FiveOneEat.GetCurrentUserResponse</code></summary>
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
await client.authentication.getCurrentUser();

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

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">logoutCurrent</a>({ ...params }) -> FiveOneEat.LogoutCurrentResponse</code></summary>
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
await client.authentication.logoutCurrent();

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

**request:** `FiveOneEat.LogoutCurrentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">logoutAll</a>() -> FiveOneEat.LogoutAllResponse</code></summary>
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
await client.authentication.logoutAll();

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

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">getUserTokens</a>() -> FiveOneEat.GetUserTokensResponse</code></summary>
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
await client.authentication.getUserTokens();

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

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">revokeToken</a>({ ...params }) -> FiveOneEat.RevokeTokenResponse</code></summary>
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
await client.authentication.revokeToken({
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

**request:** `FiveOneEat.RevokeTokenRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">registerBusiness</a>({ ...params }) -> FiveOneEat.RegisterBusinessResponse</code></summary>
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
await client.authentication.registerBusiness({
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

**request:** `FiveOneEat.RegisterBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">loginBusiness</a>({ ...params }) -> FiveOneEat.LoginBusinessResponse</code></summary>
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
await client.authentication.loginBusiness({
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

**request:** `FiveOneEat.LoginBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">getBusinessMe</a>() -> FiveOneEat.GetBusinessMeResponse</code></summary>
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
await client.authentication.getBusinessMe();

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

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">logoutBusiness</a>({ ...params }) -> FiveOneEat.LogoutBusinessResponse</code></summary>
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
await client.authentication.logoutBusiness();

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

**request:** `FiveOneEat.LogoutBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">logoutAllBusiness</a>() -> FiveOneEat.LogoutAllBusinessResponse</code></summary>
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
await client.authentication.logoutAllBusiness();

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

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">getBusinessTokens</a>() -> FiveOneEat.GetBusinessTokensResponse</code></summary>
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
await client.authentication.getBusinessTokens();

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

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">revokeBusinessToken</a>({ ...params }) -> FiveOneEat.RevokeBusinessTokenResponse</code></summary>
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
await client.authentication.revokeBusinessToken({
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

**request:** `FiveOneEat.RevokeBusinessTokenRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.authentication.<a href="/src/api/resources/authentication/client/Client.ts">switchBusiness</a>({ ...params }) -> FiveOneEat.SwitchBusinessResponse</code></summary>
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
await client.authentication.switchBusiness({
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

**request:** `FiveOneEat.SwitchBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `AuthenticationClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Broadcasting
<details><summary><code>client.broadcasting.<a href="/src/api/resources/broadcasting/client/Client.ts">channelAuthAuthenticate</a>({ ...params }) -> number</code></summary>
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
await client.broadcasting.channelAuthAuthenticate({
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

**request:** `FiveOneEat.ChannelAuthAuthenticateRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BroadcastingClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Bulletins
<details><summary><code>client.bulletins.<a href="/src/api/resources/bulletins/client/Client.ts">listBulletins</a>() -> FiveOneEat.ListBulletinsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bulletins.listBulletins();

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

<details><summary><code>client.bulletins.<a href="/src/api/resources/bulletins/client/Client.ts">createBulletin</a>({ ...params }) -> FiveOneEat.CreateBulletinResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bulletins.createBulletin({
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

**request:** `FiveOneEat.StoreBulletinRequest` 
    
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

<details><summary><code>client.bulletins.<a href="/src/api/resources/bulletins/client/Client.ts">getBulletin</a>({ ...params }) -> FiveOneEat.GetBulletinResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bulletins.getBulletin({
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

**request:** `FiveOneEat.GetBulletinRequest` 
    
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

<details><summary><code>client.bulletins.<a href="/src/api/resources/bulletins/client/Client.ts">updateBulletin</a>({ ...params }) -> FiveOneEat.UpdateBulletinResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bulletins.updateBulletin({
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

**request:** `FiveOneEat.UpdateBulletinRequest` 
    
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

<details><summary><code>client.bulletins.<a href="/src/api/resources/bulletins/client/Client.ts">deleteBulletin</a>({ ...params }) -> FiveOneEat.DeleteBulletinResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bulletins.deleteBulletin({
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

**request:** `FiveOneEat.DeleteBulletinRequest` 
    
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

<details><summary><code>client.bulletins.<a href="/src/api/resources/bulletins/client/Client.ts">toggleBulletinPinned</a>({ ...params }) -> FiveOneEat.ToggleBulletinPinnedResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bulletins.toggleBulletinPinned({
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

**request:** `FiveOneEat.ToggleBulletinPinnedRequest` 
    
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

<details><summary><code>client.bulletins.<a href="/src/api/resources/bulletins/client/Client.ts">toggleBulletinPublished</a>({ ...params }) -> FiveOneEat.ToggleBulletinPublishedResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.bulletins.toggleBulletinPublished({
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

**request:** `FiveOneEat.ToggleBulletinPublishedRequest` 
    
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

## Business Content
<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">getBusinessMenus</a>({ ...params }) -> FiveOneEat.GetBusinessMenusResponse</code></summary>
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
await client.businessContent.getBusinessMenus({
    handle: "katzs-deli"
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

**request:** `FiveOneEat.GetBusinessMenusRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">getBusinessPhotos</a>({ ...params }) -> FiveOneEat.GetBusinessPhotosResponse</code></summary>
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
await client.businessContent.getBusinessPhotos({
    handle: "katzs-deli"
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

**request:** `FiveOneEat.GetBusinessPhotosRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">getBusinessBulletins</a>({ ...params }) -> FiveOneEat.GetBusinessBulletinsResponse</code></summary>
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
await client.businessContent.getBusinessBulletins({
    handle: "katzs-deli"
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

**request:** `FiveOneEat.GetBusinessBulletinsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">getBulletinComments</a>({ ...params }) -> FiveOneEat.GetBulletinCommentsResponse</code></summary>
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
await client.businessContent.getBulletinComments({
    handle: "katzs-deli",
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

**request:** `FiveOneEat.GetBulletinCommentsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">createBulletinComment</a>({ ...params }) -> FiveOneEat.CreateBulletinCommentResponse</code></summary>
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
await client.businessContent.createBulletinComment({
    handle: "katzs-deli",
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

**request:** `FiveOneEat.StoreBulletinCommentRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">getBusinessEvents</a>({ ...params }) -> FiveOneEat.GetBusinessEventsResponse</code></summary>
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
await client.businessContent.getBusinessEvents({
    handle: "katzs-deli"
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

**request:** `FiveOneEat.GetBusinessEventsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">getBusinessEvent</a>({ ...params }) -> FiveOneEat.GetBusinessEventResponse</code></summary>
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
await client.businessContent.getBusinessEvent({
    handle: "katzs-deli",
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

**request:** `FiveOneEat.GetBusinessEventRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">storeEventRsvp</a>({ ...params }) -> FiveOneEat.StoreEventRsvpResponse</code></summary>
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
await client.businessContent.storeEventRsvp({
    handle: "katzs-deli",
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

**request:** `FiveOneEat.StoreEventRsvpRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessContent.<a href="/src/api/resources/businessContent/client/Client.ts">destroyEventRsvp</a>({ ...params }) -> number</code></summary>
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
await client.businessContent.destroyEventRsvp({
    handle: "katzs-deli",
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

**request:** `FiveOneEat.DestroyEventRsvpRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessContentClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Profile
<details><summary><code>client.businessProfile.<a href="/src/api/resources/businessProfile/client/Client.ts">businessProfileShow</a>() -> FiveOneEat.BusinessProfileShowResponse</code></summary>
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
await client.businessProfile.businessProfileShow();

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

**requestOptions:** `BusinessProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProfile.<a href="/src/api/resources/businessProfile/client/Client.ts">updateBusinessProfile</a>({ ...params }) -> FiveOneEat.UpdateBusinessProfileResponse</code></summary>
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
await client.businessProfile.updateBusinessProfile();

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

**request:** `FiveOneEat.UpdateBusinessProfileRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProfile.<a href="/src/api/resources/businessProfile/client/Client.ts">uploadBusinessLogo</a>({ ...params }) -> FiveOneEat.UploadBusinessLogoResponse</code></summary>
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
await client.businessProfile.uploadBusinessLogo({
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

**request:** `FiveOneEat.UploadLogoRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProfile.<a href="/src/api/resources/businessProfile/client/Client.ts">deleteBusinessLogo</a>() -> FiveOneEat.DeleteBusinessLogoResponse</code></summary>
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
await client.businessProfile.deleteBusinessLogo();

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

**requestOptions:** `BusinessProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProfile.<a href="/src/api/resources/businessProfile/client/Client.ts">syncBusinessCuisines</a>({ ...params }) -> FiveOneEat.SyncBusinessCuisinesResponse</code></summary>
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
await client.businessProfile.syncBusinessCuisines({
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

**request:** `FiveOneEat.SyncCuisinesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProfile.<a href="/src/api/resources/businessProfile/client/Client.ts">syncBusinessCertifications</a>({ ...params }) -> FiveOneEat.SyncBusinessCertificationsResponse</code></summary>
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
await client.businessProfile.syncBusinessCertifications({
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

**request:** `FiveOneEat.SyncCertificationsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProfileClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Business Profiles
<details><summary><code>client.businessProfiles.<a href="/src/api/resources/businessProfiles/client/Client.ts">profileShow</a>({ ...params }) -> FiveOneEat.ProfileShowResponse</code></summary>
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
await client.businessProfiles.profileShow({
    handle: "katzs-deli"
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

**request:** `FiveOneEat.ProfileShowRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProfilesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProfiles.<a href="/src/api/resources/businessProfiles/client/Client.ts">favoritesBusiness</a>({ ...params }) -> FiveOneEat.FavoritesBusinessResponse</code></summary>
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
await client.businessProfiles.favoritesBusiness({
    handle: "katzs-deli"
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

**request:** `FiveOneEat.FavoritesBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProfilesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.businessProfiles.<a href="/src/api/resources/businessProfiles/client/Client.ts">unfavoritesBusiness</a>({ ...params }) -> Record&lt;string, unknown&gt;</code></summary>
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
await client.businessProfiles.unfavoritesBusiness({
    handle: "katzs-deli"
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

**request:** `FiveOneEat.UnfavoritesBusinessRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `BusinessProfilesClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Customer Messaging
<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">getCustomerConversations</a>({ ...params }) -> FiveOneEat.GetCustomerConversationsResponse</code></summary>
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
await client.customerMessaging.getCustomerConversations();

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

**request:** `FiveOneEat.GetCustomerConversationsRequest` 
    
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

<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">startConversation</a>({ ...params }) -> FiveOneEat.StartConversationResponse</code></summary>
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
await client.customerMessaging.startConversation({
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

**request:** `FiveOneEat.StartConversationRequest` 
    
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

<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">getConversation</a>({ ...params }) -> FiveOneEat.GetConversationResponse</code></summary>
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
await client.customerMessaging.getConversation({
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

**request:** `FiveOneEat.GetConversationRequest` 
    
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

<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">deleteConversation</a>({ ...params }) -> number</code></summary>
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
await client.customerMessaging.deleteConversation({
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

**request:** `FiveOneEat.DeleteConversationRequest` 
    
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

<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">getConversationMessages</a>({ ...params }) -> FiveOneEat.GetConversationMessagesResponse</code></summary>
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
await client.customerMessaging.getConversationMessages({
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

**request:** `FiveOneEat.GetConversationMessagesRequest` 
    
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

<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">sendMessage</a>({ ...params }) -> FiveOneEat.SendMessageResponse</code></summary>
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
await client.customerMessaging.sendMessage({
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

**request:** `FiveOneEat.SendMessageRequest` 
    
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

<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">markMessagesAsRead</a>({ ...params }) -> number</code></summary>
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
await client.customerMessaging.markMessagesAsRead({
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

**request:** `FiveOneEat.MarkMessagesAsReadRequest` 
    
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

<details><summary><code>client.customerMessaging.<a href="/src/api/resources/customerMessaging/client/Client.ts">getUnreadCount</a>({ ...params }) -> number</code></summary>
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
await client.customerMessaging.getUnreadCount({
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

**request:** `FiveOneEat.GetUnreadCountRequest` 
    
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

## Discovery
<details><summary><code>client.discovery.<a href="/src/api/resources/discovery/client/Client.ts">exploreBusinesses</a>({ ...params }) -> FiveOneEat.ExploreBusinessesResponse</code></summary>
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
await client.discovery.exploreBusinesses({
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

**request:** `FiveOneEat.ExploreBusinessesRequest` 
    
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

<details><summary><code>client.discovery.<a href="/src/api/resources/discovery/client/Client.ts">getDiscoveryFeed</a>({ ...params }) -> FiveOneEat.DiscoveryFeedResource</code></summary>
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
await client.discovery.getDiscoveryFeed({
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

**request:** `FiveOneEat.GetDiscoveryFeedRequest` 
    
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

<details><summary><code>client.discovery.<a href="/src/api/resources/discovery/client/Client.ts">getDiscoveryHighlights</a>() -> FiveOneEat.DiscoveryHighlightsResource</code></summary>
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
await client.discovery.getDiscoveryHighlights();

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

<details><summary><code>client.discovery.<a href="/src/api/resources/discovery/client/Client.ts">getDiscoveryCategories</a>() -> FiveOneEat.GetDiscoveryCategoriesResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a list of all business categories that have businesses.
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
await client.discovery.getDiscoveryCategories();

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

<details><summary><code>client.discovery.<a href="/src/api/resources/discovery/client/Client.ts">getDiscoveryCuisines</a>() -> FiveOneEat.GetDiscoveryCuisinesResponse</code></summary>
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
await client.discovery.getDiscoveryCuisines();

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

<details><summary><code>client.discovery.<a href="/src/api/resources/discovery/client/Client.ts">getDiscoveryCertifications</a>() -> FiveOneEat.GetDiscoveryCertificationsResponse</code></summary>
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
await client.discovery.getDiscoveryCertifications();

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

<details><summary><code>client.discovery.<a href="/src/api/resources/discovery/client/Client.ts">getCategoryBusinesses</a>({ ...params }) -> FiveOneEat.GetCategoryBusinessesResponse</code></summary>
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
await client.discovery.getCategoryBusinesses({
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

**request:** `FiveOneEat.GetCategoryBusinessesRequest` 
    
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

## Editorials
<details><summary><code>client.editorials.<a href="/src/api/resources/editorials/client/Client.ts">listEditorials</a>() -> FiveOneEat.ListEditorialsResponse</code></summary>
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
await client.editorials.listEditorials();

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

<details><summary><code>client.editorials.<a href="/src/api/resources/editorials/client/Client.ts">getEditorial</a>({ ...params }) -> FiveOneEat.GetEditorialResponse</code></summary>
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
await client.editorials.getEditorial({
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

**request:** `FiveOneEat.GetEditorialRequest` 
    
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

## Events
<details><summary><code>client.events.<a href="/src/api/resources/events/client/Client.ts">getEventFeed</a>({ ...params }) -> FiveOneEat.GetEventFeedResponse</code></summary>
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
await client.events.getEventFeed({
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

**request:** `FiveOneEat.GetEventFeedRequest` 
    
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

## Menus
<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">listMenus</a>() -> FiveOneEat.ListMenusResponse</code></summary>
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
await client.menus.listMenus();

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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">createMenu</a>({ ...params }) -> FiveOneEat.CreateMenuResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.createMenu({
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

**request:** `FiveOneEat.StoreMenuRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">getMenu</a>({ ...params }) -> FiveOneEat.GetMenuResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.getMenu({
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

**request:** `FiveOneEat.GetMenuRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">updateMenu</a>({ ...params }) -> FiveOneEat.UpdateMenuResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.updateMenu({
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

**request:** `FiveOneEat.UpdateMenuRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">deleteMenu</a>({ ...params }) -> FiveOneEat.DeleteMenuResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.deleteMenu({
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

**request:** `FiveOneEat.DeleteMenuRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">listMenuGroups</a>({ ...params }) -> FiveOneEat.ListMenuGroupsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.listMenuGroups({
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

**request:** `FiveOneEat.ListMenuGroupsRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">createMenuGroup</a>({ ...params }) -> FiveOneEat.CreateMenuGroupResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.createMenuGroup({
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

**request:** `FiveOneEat.StoreMenuGroupRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">getMenuGroup</a>({ ...params }) -> FiveOneEat.GetMenuGroupResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.getMenuGroup({
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

**request:** `FiveOneEat.GetMenuGroupRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">updateMenuGroup</a>({ ...params }) -> FiveOneEat.UpdateMenuGroupResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.updateMenuGroup({
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

**request:** `FiveOneEat.UpdateMenuGroupRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">deleteMenuGroup</a>({ ...params }) -> FiveOneEat.DeleteMenuGroupResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.deleteMenuGroup({
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

**request:** `FiveOneEat.DeleteMenuGroupRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">listMenuItems</a>({ ...params }) -> FiveOneEat.ListMenuItemsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.listMenuItems({
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

**request:** `FiveOneEat.ListMenuItemsRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">createMenuItem</a>({ ...params }) -> FiveOneEat.CreateMenuItemResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.createMenuItem({
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

**request:** `FiveOneEat.StoreMenuItemRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">getMenuItem</a>({ ...params }) -> FiveOneEat.GetMenuItemResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.getMenuItem({
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

**request:** `FiveOneEat.GetMenuItemRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">updateMenuItem</a>({ ...params }) -> FiveOneEat.UpdateMenuItemResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.updateMenuItem({
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

**request:** `FiveOneEat.UpdateMenuItemRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">deleteMenuItem</a>({ ...params }) -> FiveOneEat.DeleteMenuItemResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.deleteMenuItem({
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

**request:** `FiveOneEat.DeleteMenuItemRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">listMenuItemVariations</a>({ ...params }) -> FiveOneEat.ListMenuItemVariationsResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.listMenuItemVariations({
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

**request:** `FiveOneEat.ListMenuItemVariationsRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">createMenuItemVariation</a>({ ...params }) -> FiveOneEat.CreateMenuItemVariationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.createMenuItemVariation({
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

**request:** `FiveOneEat.StoreMenuItemVariationRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">updateMenuItemVariation</a>({ ...params }) -> FiveOneEat.UpdateMenuItemVariationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.updateMenuItemVariation({
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

**request:** `FiveOneEat.UpdateMenuItemVariationRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">deleteMenuItemVariation</a>({ ...params }) -> FiveOneEat.DeleteMenuItemVariationResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.deleteMenuItemVariation({
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

**request:** `FiveOneEat.DeleteMenuItemVariationRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">listMenuItemModifiers</a>({ ...params }) -> FiveOneEat.ListMenuItemModifiersResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.menus.listMenuItemModifiers({
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

**request:** `FiveOneEat.ListMenuItemModifiersRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">attachMenuItemModifier</a>({ ...params }) -> FiveOneEat.AttachMenuItemModifierResponse</code></summary>
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
await client.menus.attachMenuItemModifier({
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

**request:** `FiveOneEat.StoreMenuItemModifierRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">detachMenuItemModifier</a>({ ...params }) -> FiveOneEat.DetachMenuItemModifierResponse</code></summary>
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
await client.menus.detachMenuItemModifier({
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

**request:** `FiveOneEat.DetachMenuItemModifierRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">reorderMenuGroups</a>({ ...params }) -> FiveOneEat.ReorderMenuGroupsResponse</code></summary>
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
await client.menus.reorderMenuGroups({
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

**request:** `FiveOneEat.ReorderMenuGroupsRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">reorderMenuItems</a>({ ...params }) -> FiveOneEat.ReorderMenuItemsResponse</code></summary>
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
await client.menus.reorderMenuItems({
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

**request:** `FiveOneEat.ReorderMenuItemsRequest` 
    
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

<details><summary><code>client.menus.<a href="/src/api/resources/menus/client/Client.ts">moveMenuItem</a>({ ...params }) -> FiveOneEat.MoveMenuItemResponse</code></summary>
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
await client.menus.moveMenuItem({
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

**request:** `FiveOneEat.MoveMenuItemRequest` 
    
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

## My Account
<details><summary><code>client.myAccount.<a href="/src/api/resources/myAccount/client/Client.ts">getMyFavorites</a>({ ...params }) -> FiveOneEat.GetMyFavoritesResponse</code></summary>
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
await client.myAccount.getMyFavorites();

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

**request:** `FiveOneEat.GetMyFavoritesRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.myAccount.<a href="/src/api/resources/myAccount/client/Client.ts">getMyRsvps</a>({ ...params }) -> FiveOneEat.GetMyRsvpsResponse</code></summary>
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
await client.myAccount.getMyRsvps({
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

**request:** `FiveOneEat.GetMyRsvpsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.myAccount.<a href="/src/api/resources/myAccount/client/Client.ts">getMyTickets</a>({ ...params }) -> FiveOneEat.GetMyTicketsResponse</code></summary>
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
await client.myAccount.getMyTickets();

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

**request:** `FiveOneEat.GetMyTicketsRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.myAccount.<a href="/src/api/resources/myAccount/client/Client.ts">getMyTicket</a>({ ...params }) -> FiveOneEat.GetMyTicketResponse</code></summary>
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
await client.myAccount.getMyTicket({
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

**requestOptions:** `MyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.myAccount.<a href="/src/api/resources/myAccount/client/Client.ts">getMyTicketOrders</a>({ ...params }) -> FiveOneEat.GetMyTicketOrdersResponse</code></summary>
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
await client.myAccount.getMyTicketOrders();

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

**request:** `FiveOneEat.GetMyTicketOrdersRequest` 
    
</dd>
</dl>

<dl>
<dd>

**requestOptions:** `MyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

<details><summary><code>client.myAccount.<a href="/src/api/resources/myAccount/client/Client.ts">getMyTicketOrder</a>({ ...params }) -> FiveOneEat.GetMyTicketOrderResponse</code></summary>
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
await client.myAccount.getMyTicketOrder({
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

**requestOptions:** `MyAccountClient.RequestOptions` 
    
</dd>
</dl>
</dd>
</dl>


</dd>
</dl>
</details>

## Push Notifications
<details><summary><code>client.pushNotifications.<a href="/src/api/resources/pushNotifications/client/Client.ts">registerPushToken</a>({ ...params }) -> FiveOneEat.RegisterPushTokenResponse</code></summary>
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
await client.pushNotifications.registerPushToken({
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

**request:** `FiveOneEat.StorePushTokenRequest` 
    
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

<details><summary><code>client.pushNotifications.<a href="/src/api/resources/pushNotifications/client/Client.ts">unregisterPushToken</a>({ ...params }) -> void</code></summary>
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
await client.pushNotifications.unregisterPushToken({
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

**request:** `FiveOneEat.UnregisterPushTokenRequest` 
    
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

## Ticketing
<details><summary><code>client.ticketing.<a href="/src/api/resources/ticketing/client/Client.ts">holdTickets</a>({ ...params }) -> FiveOneEat.HoldTicketsResponse</code></summary>
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
await client.ticketing.holdTickets({
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

**request:** `FiveOneEat.StoreTicketHoldRequest` 
    
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

<details><summary><code>client.ticketing.<a href="/src/api/resources/ticketing/client/Client.ts">releaseTicketHold</a>({ ...params }) -> void</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Release all active holds for the given session, freeing the tickets for others.
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
await client.ticketing.releaseTicketHold({
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

**request:** `FiveOneEat.ReleaseTicketHoldRequest` 
    
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

<details><summary><code>client.ticketing.<a href="/src/api/resources/ticketing/client/Client.ts">calculateTicketPrice</a>({ ...params }) -> FiveOneEat.CalculateTicketPriceResponse</code></summary>
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
await client.ticketing.calculateTicketPrice({
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

**request:** `FiveOneEat.CalculatePriceRequest` 
    
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

<details><summary><code>client.ticketing.<a href="/src/api/resources/ticketing/client/Client.ts">createPaymentIntent</a>({ ...params }) -> FiveOneEat.CreatePaymentIntentResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Create a Stripe payment intent for the tickets held in the given session.
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
await client.ticketing.createPaymentIntent({
    eventId: "eventId",
    session_id: "session_id"
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

**request:** `FiveOneEat.CreatePaymentIntentRequest` 
    
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

<details><summary><code>client.ticketing.<a href="/src/api/resources/ticketing/client/Client.ts">confirmTicketOrder</a>({ ...params }) -> FiveOneEat.ConfirmTicketOrderResponse</code></summary>
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
await client.ticketing.confirmTicketOrder({
    eventId: "eventId",
    payment_intent_id: "payment_intent_id",
    session_id: "session_id"
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

**request:** `FiveOneEat.StoreTicketOrderRequest` 
    
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

