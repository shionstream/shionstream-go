# V1DashboardCategoriesGet200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Categories** | [**[]V1DashboardCategoriesGet200ResponseCategoriesInner**](V1DashboardCategoriesGet200ResponseCategoriesInner.md) |  | 
**Genres** | [**[]V1DashboardCategoriesGet200ResponseGenresInner**](V1DashboardCategoriesGet200ResponseGenresInner.md) |  | 

## Methods

### NewV1DashboardCategoriesGet200Response

`func NewV1DashboardCategoriesGet200Response(categories []V1DashboardCategoriesGet200ResponseCategoriesInner, genres []V1DashboardCategoriesGet200ResponseGenresInner, ) *V1DashboardCategoriesGet200Response`

NewV1DashboardCategoriesGet200Response instantiates a new V1DashboardCategoriesGet200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewV1DashboardCategoriesGet200ResponseWithDefaults

`func NewV1DashboardCategoriesGet200ResponseWithDefaults() *V1DashboardCategoriesGet200Response`

NewV1DashboardCategoriesGet200ResponseWithDefaults instantiates a new V1DashboardCategoriesGet200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategories

`func (o *V1DashboardCategoriesGet200Response) GetCategories() []V1DashboardCategoriesGet200ResponseCategoriesInner`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *V1DashboardCategoriesGet200Response) GetCategoriesOk() (*[]V1DashboardCategoriesGet200ResponseCategoriesInner, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *V1DashboardCategoriesGet200Response) SetCategories(v []V1DashboardCategoriesGet200ResponseCategoriesInner)`

SetCategories sets Categories field to given value.


### GetGenres

`func (o *V1DashboardCategoriesGet200Response) GetGenres() []V1DashboardCategoriesGet200ResponseGenresInner`

GetGenres returns the Genres field if non-nil, zero value otherwise.

### GetGenresOk

`func (o *V1DashboardCategoriesGet200Response) GetGenresOk() (*[]V1DashboardCategoriesGet200ResponseGenresInner, bool)`

GetGenresOk returns a tuple with the Genres field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenres

`func (o *V1DashboardCategoriesGet200Response) SetGenres(v []V1DashboardCategoriesGet200ResponseGenresInner)`

SetGenres sets Genres field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


