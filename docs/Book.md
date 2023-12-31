# Book

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** |  | [optional] 
**Author** | Pointer to **string** |  | [optional] 
**Isbn** | Pointer to **string** |  | [optional] 
**CoverImage** | Pointer to **string** |  | [optional] 

## Methods

### NewBook

`func NewBook() *Book`

NewBook instantiates a new Book object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBookWithDefaults

`func NewBookWithDefaults() *Book`

NewBookWithDefaults instantiates a new Book object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *Book) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Book) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Book) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Book) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetAuthor

`func (o *Book) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *Book) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *Book) SetAuthor(v string)`

SetAuthor sets Author field to given value.

### HasAuthor

`func (o *Book) HasAuthor() bool`

HasAuthor returns a boolean if a field has been set.

### GetIsbn

`func (o *Book) GetIsbn() string`

GetIsbn returns the Isbn field if non-nil, zero value otherwise.

### GetIsbnOk

`func (o *Book) GetIsbnOk() (*string, bool)`

GetIsbnOk returns a tuple with the Isbn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsbn

`func (o *Book) SetIsbn(v string)`

SetIsbn sets Isbn field to given value.

### HasIsbn

`func (o *Book) HasIsbn() bool`

HasIsbn returns a boolean if a field has been set.

### GetCoverImage

`func (o *Book) GetCoverImage() string`

GetCoverImage returns the CoverImage field if non-nil, zero value otherwise.

### GetCoverImageOk

`func (o *Book) GetCoverImageOk() (*string, bool)`

GetCoverImageOk returns a tuple with the CoverImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoverImage

`func (o *Book) SetCoverImage(v string)`

SetCoverImage sets CoverImage field to given value.

### HasCoverImage

`func (o *Book) HasCoverImage() bool`

HasCoverImage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


