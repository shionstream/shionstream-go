# V1DashboardUsersGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Users** | [**[]V1DashboardUsersGet200ResponseUsersInner**](V1DashboardUsersGet200ResponseUsersInner.md) |  | 
**Total** | **float32** |  | 
**Page** | **float32** |  | 
**Limit** | **float32** |  | 

## Methods

### NewV1DashboardUsersGet200Response

`func NewV1DashboardUsersGet200Response(users []V1DashboardUsersGet200ResponseUsersInner, total float32, page float32, limit float32, ) *V1DashboardUsersGet200Response`

NewV1DashboardUsersGet200Response instantiates a new V1DashboardUsersGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DashboardUsersGet200ResponseWithDefaults

`func NewV1DashboardUsersGet200ResponseWithDefaults() *V1DashboardUsersGet200Response`

NewV1DashboardUsersGet200ResponseWithDefaults instantiates a new V1DashboardUsersGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsers

`func (o *V1DashboardUsersGet200Response) GetUsers() []V1DashboardUsersGet200ResponseUsersInner`

GetUsers returns the Users field if non-nil, zero value otherwise.

### GetUsersOk

`func (o *V1DashboardUsersGet200Response) GetUsersOk() (*[]V1DashboardUsersGet200ResponseUsersInner, bool)`

GetUsersOk returns a tuple with the Users field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsers

`func (o *V1DashboardUsersGet200Response) SetUsers(v []V1DashboardUsersGet200ResponseUsersInner)`

SetUsers sets Users field to given value.


### GetTotal

`func (o *V1DashboardUsersGet200Response) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *V1DashboardUsersGet200Response) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *V1DashboardUsersGet200Response) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *V1DashboardUsersGet200Response) GetPage() float32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *V1DashboardUsersGet200Response) GetPageOk() (*float32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *V1DashboardUsersGet200Response) SetPage(v float32)`

SetPage sets Page field to given value.


### GetLimit

`func (o *V1DashboardUsersGet200Response) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *V1DashboardUsersGet200Response) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *V1DashboardUsersGet200Response) SetLimit(v float32)`

SetLimit sets Limit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


