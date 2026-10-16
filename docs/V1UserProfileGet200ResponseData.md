# V1UserProfileGet200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Email** | **string** |  | 
**Image** | Pointer to **string** |  | [optional] 
**Role** | **string** |  | 
**Activity** | [**V1UserProfileGet200ResponseDataActivity**](V1UserProfileGet200ResponseDataActivity.md) |  | 

## Methods

### NewV1UserProfileGet200ResponseData

`func NewV1UserProfileGet200ResponseData(id string, name string, email string, role string, activity V1UserProfileGet200ResponseDataActivity, ) *V1UserProfileGet200ResponseData`

NewV1UserProfileGet200ResponseData instantiates a new V1UserProfileGet200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1UserProfileGet200ResponseDataWithDefaults

`func NewV1UserProfileGet200ResponseDataWithDefaults() *V1UserProfileGet200ResponseData`

NewV1UserProfileGet200ResponseDataWithDefaults instantiates a new V1UserProfileGet200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *V1UserProfileGet200ResponseData) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *V1UserProfileGet200ResponseData) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *V1UserProfileGet200ResponseData) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *V1UserProfileGet200ResponseData) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *V1UserProfileGet200ResponseData) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *V1UserProfileGet200ResponseData) SetName(v string)`

SetName sets Name field to given value.


### GetEmail

`func (o *V1UserProfileGet200ResponseData) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *V1UserProfileGet200ResponseData) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *V1UserProfileGet200ResponseData) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetImage

`func (o *V1UserProfileGet200ResponseData) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *V1UserProfileGet200ResponseData) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *V1UserProfileGet200ResponseData) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *V1UserProfileGet200ResponseData) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetRole

`func (o *V1UserProfileGet200ResponseData) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *V1UserProfileGet200ResponseData) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *V1UserProfileGet200ResponseData) SetRole(v string)`

SetRole sets Role field to given value.


### GetActivity

`func (o *V1UserProfileGet200ResponseData) GetActivity() V1UserProfileGet200ResponseDataActivity`

GetActivity returns the Activity field if non-nil, zero value otherwise.

### GetActivityOk

`func (o *V1UserProfileGet200ResponseData) GetActivityOk() (*V1UserProfileGet200ResponseDataActivity, bool)`

GetActivityOk returns a tuple with the Activity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivity

`func (o *V1UserProfileGet200ResponseData) SetActivity(v V1UserProfileGet200ResponseDataActivity)`

SetActivity sets Activity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


