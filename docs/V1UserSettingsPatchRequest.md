# V1UserSettingsPatchRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Profile** | Pointer to [**V1UserSettingsPatchRequestProfile**](V1UserSettingsPatchRequestProfile.md) |  | [optional] 
**Player** | Pointer to [**V1UserSettingsPatchRequestPlayer**](V1UserSettingsPatchRequestPlayer.md) |  | [optional] 
**Notifications** | Pointer to [**V1UserSettingsPatchRequestNotifications**](V1UserSettingsPatchRequestNotifications.md) |  | [optional] 

## Methods

### NewV1UserSettingsPatchRequest

`func NewV1UserSettingsPatchRequest() *V1UserSettingsPatchRequest`

NewV1UserSettingsPatchRequest instantiates a new V1UserSettingsPatchRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1UserSettingsPatchRequestWithDefaults

`func NewV1UserSettingsPatchRequestWithDefaults() *V1UserSettingsPatchRequest`

NewV1UserSettingsPatchRequestWithDefaults instantiates a new V1UserSettingsPatchRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProfile

`func (o *V1UserSettingsPatchRequest) GetProfile() V1UserSettingsPatchRequestProfile`

GetProfile returns the Profile field if non-nil, zero value otherwise.

### GetProfileOk

`func (o *V1UserSettingsPatchRequest) GetProfileOk() (*V1UserSettingsPatchRequestProfile, bool)`

GetProfileOk returns a tuple with the Profile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfile

`func (o *V1UserSettingsPatchRequest) SetProfile(v V1UserSettingsPatchRequestProfile)`

SetProfile sets Profile field to given value.

### HasProfile

`func (o *V1UserSettingsPatchRequest) HasProfile() bool`

HasProfile returns a boolean if a field has been set.

### GetPlayer

`func (o *V1UserSettingsPatchRequest) GetPlayer() V1UserSettingsPatchRequestPlayer`

GetPlayer returns the Player field if non-nil, zero value otherwise.

### GetPlayerOk

`func (o *V1UserSettingsPatchRequest) GetPlayerOk() (*V1UserSettingsPatchRequestPlayer, bool)`

GetPlayerOk returns a tuple with the Player field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlayer

`func (o *V1UserSettingsPatchRequest) SetPlayer(v V1UserSettingsPatchRequestPlayer)`

SetPlayer sets Player field to given value.

### HasPlayer

`func (o *V1UserSettingsPatchRequest) HasPlayer() bool`

HasPlayer returns a boolean if a field has been set.

### GetNotifications

`func (o *V1UserSettingsPatchRequest) GetNotifications() V1UserSettingsPatchRequestNotifications`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *V1UserSettingsPatchRequest) GetNotificationsOk() (*V1UserSettingsPatchRequestNotifications, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *V1UserSettingsPatchRequest) SetNotifications(v V1UserSettingsPatchRequestNotifications)`

SetNotifications sets Notifications field to given value.

### HasNotifications

`func (o *V1UserSettingsPatchRequest) HasNotifications() bool`

HasNotifications returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


