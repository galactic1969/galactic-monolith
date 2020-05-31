[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/intent"](../modules/_models_intent_.md) › [ExecuteResults](_models_intent_.executeresults.md)

# Class: ExecuteResults

1デバイスの1CommandにおけるExecutionの結果の配列。1デバイスに対して2つ以上のコマンドが発生する場合は、コマンド毎の結果を配列に入れて、mergeする

## Hierarchy

* [Array](_models_intent_.executeresults.md#static-array)‹[ExecuteResult](_models_intent_.executeresult.md)›

  ↳ **ExecuteResults**

## Indexable

* \[ **n**: *number*\]: [ExecuteResult](_models_intent_.executeresult.md)

1デバイスの1CommandにおけるExecutionの結果の配列。1デバイスに対して2つ以上のコマンドが発生する場合は、コマンド毎の結果を配列に入れて、mergeする

## Index

### Properties

* [length](_models_intent_.executeresults.md#length)
* [Array](_models_intent_.executeresults.md#static-array)

### Methods

* [[Symbol.iterator]](_models_intent_.executeresults.md#[symbol.iterator])
* [[Symbol.unscopables]](_models_intent_.executeresults.md#[symbol.unscopables])
* [concat](_models_intent_.executeresults.md#concat)
* [copyWithin](_models_intent_.executeresults.md#copywithin)
* [entries](_models_intent_.executeresults.md#entries)
* [every](_models_intent_.executeresults.md#every)
* [fill](_models_intent_.executeresults.md#fill)
* [filter](_models_intent_.executeresults.md#filter)
* [find](_models_intent_.executeresults.md#find)
* [findIndex](_models_intent_.executeresults.md#findindex)
* [flat](_models_intent_.executeresults.md#flat)
* [flatMap](_models_intent_.executeresults.md#flatmap)
* [forEach](_models_intent_.executeresults.md#foreach)
* [includes](_models_intent_.executeresults.md#includes)
* [indexOf](_models_intent_.executeresults.md#indexof)
* [join](_models_intent_.executeresults.md#join)
* [keys](_models_intent_.executeresults.md#keys)
* [lastIndexOf](_models_intent_.executeresults.md#lastindexof)
* [map](_models_intent_.executeresults.md#map)
* [mergeResult](_models_intent_.executeresults.md#mergeresult)
* [pop](_models_intent_.executeresults.md#pop)
* [push](_models_intent_.executeresults.md#push)
* [reduce](_models_intent_.executeresults.md#reduce)
* [reduceRight](_models_intent_.executeresults.md#reduceright)
* [reverse](_models_intent_.executeresults.md#reverse)
* [shift](_models_intent_.executeresults.md#shift)
* [slice](_models_intent_.executeresults.md#slice)
* [some](_models_intent_.executeresults.md#some)
* [sort](_models_intent_.executeresults.md#sort)
* [splice](_models_intent_.executeresults.md#splice)
* [toLocaleString](_models_intent_.executeresults.md#tolocalestring)
* [toString](_models_intent_.executeresults.md#tostring)
* [unshift](_models_intent_.executeresults.md#unshift)
* [values](_models_intent_.executeresults.md#values)

## Properties

###  length

• **length**: *number*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[length](_models_intent_.executeresults.md#length)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1215

Gets or sets the length of the array. This is a number one higher than the highest element defined in an array.

___

### `Static` Array

▪ **Array**: *ArrayConstructor*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1385

## Methods

###  [Symbol.iterator]

▸ **[Symbol.iterator]**(): *IterableIterator‹[ExecuteResult](_models_intent_.executeresult.md)›*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[[Symbol.iterator]](_models_intent_.executeresults.md#[symbol.iterator])*

Defined in node_modules/typescript/lib/lib.es2015.iterable.d.ts:60

Iterator

**Returns:** *IterableIterator‹[ExecuteResult](_models_intent_.executeresult.md)›*

___

###  [Symbol.unscopables]

▸ **[Symbol.unscopables]**(): *object*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[[Symbol.unscopables]](_models_intent_.executeresults.md#[symbol.unscopables])*

Defined in node_modules/typescript/lib/lib.es2015.symbol.wellknown.d.ts:94

Returns an object whose properties have the value 'true'
when they will be absent when used in a 'with' statement.

**Returns:** *object*

* **copyWithin**: *boolean*

* **entries**: *boolean*

* **fill**: *boolean*

* **find**: *boolean*

* **findIndex**: *boolean*

* **keys**: *boolean*

* **values**: *boolean*

___

###  concat

▸ **concat**(...`items`: ConcatArray‹[ExecuteResult](_models_intent_.executeresult.md)›[]): *[ExecuteResult](_models_intent_.executeresult.md)[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[concat](_models_intent_.executeresults.md#concat)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1237

Combines two or more arrays.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`...items` | ConcatArray‹[ExecuteResult](_models_intent_.executeresult.md)›[] | Additional items to add to the end of array1.  |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)[]*

▸ **concat**(...`items`: T | ConcatArray‹T›[]): *[ExecuteResult](_models_intent_.executeresult.md)[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[concat](_models_intent_.executeresults.md#concat)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1242

Combines two or more arrays.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`...items` | T &#124; ConcatArray‹T›[] | Additional items to add to the end of array1.  |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)[]*

___

###  copyWithin

▸ **copyWithin**(`target`: number, `start`: number, `end?`: undefined | number): *this*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[copyWithin](_models_intent_.executeresults.md#copywithin)*

Defined in node_modules/typescript/lib/lib.es2015.core.d.ts:64

Returns the this object after copying a section of the array identified by start and end
to the same array starting at position target

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`target` | number | If target is negative, it is treated as length+target where length is the length of the array. |
`start` | number | If start is negative, it is treated as length+start. If end is negative, it is treated as length+end. |
`end?` | undefined &#124; number | If not specified, length of the this object is used as its default value.  |

**Returns:** *this*

___

###  entries

▸ **entries**(): *IterableIterator‹[number, [ExecuteResult](_models_intent_.executeresult.md)]›*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[entries](_models_intent_.executeresults.md#entries)*

Defined in node_modules/typescript/lib/lib.es2015.iterable.d.ts:65

Returns an iterable of key, value pairs for every entry in the array

**Returns:** *IterableIterator‹[number, [ExecuteResult](_models_intent_.executeresult.md)]›*

___

###  every

▸ **every**(`callbackfn`: function, `thisArg?`: any): *boolean*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[every](_models_intent_.executeresults.md#every)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1310

Determines whether all the members of an array satisfy the specified test.

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to three arguments. The every method calls
the callbackfn function for each element in the array until the callbackfn returns a value
which is coercible to the Boolean value false, or until the end of the array.

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *unknown*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

An object to which the this keyword can refer in the callbackfn function.
If thisArg is omitted, undefined is used as the this value.

**Returns:** *boolean*

___

###  fill

▸ **fill**(`value`: [ExecuteResult](_models_intent_.executeresult.md), `start?`: undefined | number, `end?`: undefined | number): *this*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[fill](_models_intent_.executeresults.md#fill)*

Defined in node_modules/typescript/lib/lib.es2015.core.d.ts:53

Returns the this object after filling the section identified by start and end with value

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) | value to fill array section with |
`start?` | undefined &#124; number | index to start filling the array at. If start is negative, it is treated as length+start where length is the length of the array. |
`end?` | undefined &#124; number | index to stop filling the array at. If end is negative, it is treated as length+end.  |

**Returns:** *this*

___

###  filter

▸ **filter**<**S**>(`callbackfn`: function, `thisArg?`: any): *S[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[filter](_models_intent_.executeresults.md#filter)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1337

Returns the elements of an array that meet the condition specified in a callback function.

**Type parameters:**

▪ **S**: *[ExecuteResult](_models_intent_.executeresult.md)*

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to three arguments. The filter method calls the callbackfn function one time for each element in the array.

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *value is S*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value.

**Returns:** *S[]*

▸ **filter**(`callbackfn`: function, `thisArg?`: any): *[ExecuteResult](_models_intent_.executeresult.md)[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[filter](_models_intent_.executeresults.md#filter)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1343

Returns the elements of an array that meet the condition specified in a callback function.

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to three arguments. The filter method calls the callbackfn function one time for each element in the array.

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *unknown*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value.

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)[]*

___

###  find

▸ **find**<**S**>(`predicate`: function, `thisArg?`: any): *S | undefined*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[find](_models_intent_.executeresults.md#find)*

Defined in node_modules/typescript/lib/lib.es2015.core.d.ts:31

Returns the value of the first element in the array where predicate is true, and undefined
otherwise.

**Type parameters:**

▪ **S**: *[ExecuteResult](_models_intent_.executeresult.md)*

**Parameters:**

▪ **predicate**: *function*

find calls predicate once for each element of the array, in ascending
order, until it finds one where predicate returns true. If such an element is found, find
immediately returns that element value. Otherwise, find returns undefined.

▸ (`this`: void, `value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `obj`: [ExecuteResult](_models_intent_.executeresult.md)[]): *value is S*

**Parameters:**

Name | Type |
------ | ------ |
`this` | void |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`obj` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

If provided, it will be used as the this value for each invocation of
predicate. If it is not provided, undefined is used instead.

**Returns:** *S | undefined*

▸ **find**(`predicate`: function, `thisArg?`: any): *[ExecuteResult](_models_intent_.executeresult.md) | undefined*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[find](_models_intent_.executeresults.md#find)*

Defined in node_modules/typescript/lib/lib.es2015.core.d.ts:32

**Parameters:**

▪ **predicate**: *function*

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `obj`: [ExecuteResult](_models_intent_.executeresult.md)[]): *unknown*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`obj` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md) | undefined*

___

###  findIndex

▸ **findIndex**(`predicate`: function, `thisArg?`: any): *number*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[findIndex](_models_intent_.executeresults.md#findindex)*

Defined in node_modules/typescript/lib/lib.es2015.core.d.ts:43

Returns the index of the first element in the array where predicate is true, and -1
otherwise.

**Parameters:**

▪ **predicate**: *function*

find calls predicate once for each element of the array, in ascending
order, until it finds one where predicate returns true. If such an element is found,
findIndex immediately returns that element index. Otherwise, findIndex returns -1.

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `obj`: [ExecuteResult](_models_intent_.executeresult.md)[]): *unknown*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`obj` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

If provided, it will be used as the this value for each invocation of
predicate. If it is not provided, undefined is used instead.

**Returns:** *number*

___

###  flat

▸ **flat**<**U**>(`this`: U[][][][][][][][], `depth`: 7): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:158

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[][][][][][][][] | - |
`depth` | 7 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`this`: U[][][][][][][], `depth`: 6): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:166

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[][][][][][][] | - |
`depth` | 6 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`this`: U[][][][][][], `depth`: 5): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:174

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[][][][][][] | - |
`depth` | 5 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`this`: U[][][][][], `depth`: 4): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:182

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[][][][][] | - |
`depth` | 4 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`this`: U[][][][], `depth`: 3): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:190

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[][][][] | - |
`depth` | 3 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`this`: U[][][], `depth`: 2): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:198

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[][][] | - |
`depth` | 2 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`this`: U[][], `depth?`: undefined | 1): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:206

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[][] | - |
`depth?` | undefined &#124; 1 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`this`: U[], `depth`: 0): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:214

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`this` | U[] | - |
`depth` | 0 | The maximum recursion depth  |

**Returns:** *U[]*

▸ **flat**<**U**>(`depth?`: undefined | number): *any[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flat](_models_intent_.executeresults.md#flat)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:222

Returns a new array with all sub-array elements concatenated into it recursively up to the
specified depth. If no depth is provided, flat method defaults to the depth of 1.

**Type parameters:**

▪ **U**

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`depth?` | undefined &#124; number | The maximum recursion depth  |

**Returns:** *any[]*

___

###  flatMap

▸ **flatMap**<**U**, **This**>(`callback`: function, `thisArg?`: This): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[flatMap](_models_intent_.executeresults.md#flatmap)*

Defined in node_modules/typescript/lib/lib.es2019.array.d.ts:147

Calls a defined callback function on each element of an array. Then, flattens the result into
a new array.
This is identical to a map followed by flat with depth 1.

**Type parameters:**

▪ **U**

▪ **This**

**Parameters:**

▪ **callback**: *function*

A function that accepts up to three arguments. The flatMap method calls the
callback function one time for each element in the array.

▸ (`this`: This, `value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *U | ReadonlyArray‹U›*

**Parameters:**

Name | Type |
------ | ------ |
`this` | This |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *This*

An object to which the this keyword can refer in the callback function. If
thisArg is omitted, undefined is used as the this value.

**Returns:** *U[]*

___

###  forEach

▸ **forEach**(`callbackfn`: function, `thisArg?`: any): *void*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[forEach](_models_intent_.executeresults.md#foreach)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1325

Performs the specified action for each element in an array.

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to three arguments. forEach calls the callbackfn function one time for each element in the array.

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *void*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value.

**Returns:** *void*

___

###  includes

▸ **includes**(`searchElement`: [ExecuteResult](_models_intent_.executeresult.md), `fromIndex?`: undefined | number): *boolean*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[includes](_models_intent_.executeresults.md#includes)*

Defined in node_modules/typescript/lib/lib.es2016.array.include.d.ts:27

Determines whether an array includes a certain element, returning true or false as appropriate.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`searchElement` | [ExecuteResult](_models_intent_.executeresult.md) | The element to search for. |
`fromIndex?` | undefined &#124; number | The position in this array at which to begin searching for searchElement.  |

**Returns:** *boolean*

___

###  indexOf

▸ **indexOf**(`searchElement`: [ExecuteResult](_models_intent_.executeresult.md), `fromIndex?`: undefined | number): *number*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[indexOf](_models_intent_.executeresults.md#indexof)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1295

Returns the index of the first occurrence of a value in an array.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`searchElement` | [ExecuteResult](_models_intent_.executeresult.md) | The value to locate in the array. |
`fromIndex?` | undefined &#124; number | The array index at which to begin the search. If fromIndex is omitted, the search starts at index 0.  |

**Returns:** *number*

___

###  join

▸ **join**(`separator?`: undefined | string): *string*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[join](_models_intent_.executeresults.md#join)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1247

Adds all the elements of an array separated by the specified separator string.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`separator?` | undefined &#124; string | A string used to separate one element of an array from the next in the resulting String. If omitted, the array elements are separated with a comma.  |

**Returns:** *string*

___

###  keys

▸ **keys**(): *IterableIterator‹number›*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[keys](_models_intent_.executeresults.md#keys)*

Defined in node_modules/typescript/lib/lib.es2015.iterable.d.ts:70

Returns an iterable of keys in the array

**Returns:** *IterableIterator‹number›*

___

###  lastIndexOf

▸ **lastIndexOf**(`searchElement`: [ExecuteResult](_models_intent_.executeresult.md), `fromIndex?`: undefined | number): *number*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[lastIndexOf](_models_intent_.executeresults.md#lastindexof)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1301

Returns the index of the last occurrence of a specified value in an array.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`searchElement` | [ExecuteResult](_models_intent_.executeresult.md) | The value to locate in the array. |
`fromIndex?` | undefined &#124; number | The array index at which to begin the search. If fromIndex is omitted, the search starts at the last index in the array.  |

**Returns:** *number*

___

###  map

▸ **map**<**U**>(`callbackfn`: function, `thisArg?`: any): *U[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[map](_models_intent_.executeresults.md#map)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1331

Calls a defined callback function on each element of an array, and returns an array that contains the results.

**Type parameters:**

▪ **U**

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to three arguments. The map method calls the callbackfn function one time for each element in the array.

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *U*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

An object to which the this keyword can refer in the callbackfn function. If thisArg is omitted, undefined is used as the this value.

**Returns:** *U[]*

___

###  mergeResult

▸ **mergeResult**(): *[ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md)*

*Defined in [src/models/intent.ts:272](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L272)*

**Returns:** *[ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md)*

___

###  pop

▸ **pop**(): *[ExecuteResult](_models_intent_.executeresult.md) | undefined*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[pop](_models_intent_.executeresults.md#pop)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1227

Removes the last element from an array and returns it.

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md) | undefined*

___

###  push

▸ **push**(...`items`: [ExecuteResult](_models_intent_.executeresult.md)[]): *number*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[push](_models_intent_.executeresults.md#push)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1232

Appends new elements to an array, and returns the new length of the array.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`...items` | [ExecuteResult](_models_intent_.executeresult.md)[] | New elements of the Array.  |

**Returns:** *number*

___

###  reduce

▸ **reduce**(`callbackfn`: function): *[ExecuteResult](_models_intent_.executeresult.md)*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[reduce](_models_intent_.executeresults.md#reduce)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1349

Calls the specified callback function for all the elements in an array. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to four arguments. The reduce method calls the callbackfn function one time for each element in the array.

▸ (`previousValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentIndex`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *[ExecuteResult](_models_intent_.executeresult.md)*

**Parameters:**

Name | Type |
------ | ------ |
`previousValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentIndex` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

▸ **reduce**(`callbackfn`: function, `initialValue`: [ExecuteResult](_models_intent_.executeresult.md)): *[ExecuteResult](_models_intent_.executeresult.md)*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[reduce](_models_intent_.executeresults.md#reduce)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1350

**Parameters:**

▪ **callbackfn**: *function*

▸ (`previousValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentIndex`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *[ExecuteResult](_models_intent_.executeresult.md)*

**Parameters:**

Name | Type |
------ | ------ |
`previousValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentIndex` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪ **initialValue**: *[ExecuteResult](_models_intent_.executeresult.md)*

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

▸ **reduce**<**U**>(`callbackfn`: function, `initialValue`: U): *U*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[reduce](_models_intent_.executeresults.md#reduce)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1356

Calls the specified callback function for all the elements in an array. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

**Type parameters:**

▪ **U**

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to four arguments. The reduce method calls the callbackfn function one time for each element in the array.

▸ (`previousValue`: U, `currentValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentIndex`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *U*

**Parameters:**

Name | Type |
------ | ------ |
`previousValue` | U |
`currentValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentIndex` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪ **initialValue**: *U*

If initialValue is specified, it is used as the initial value to start the accumulation. The first call to the callbackfn function provides this value as an argument instead of an array value.

**Returns:** *U*

___

###  reduceRight

▸ **reduceRight**(`callbackfn`: function): *[ExecuteResult](_models_intent_.executeresult.md)*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[reduceRight](_models_intent_.executeresults.md#reduceright)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1362

Calls the specified callback function for all the elements in an array, in descending order. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to four arguments. The reduceRight method calls the callbackfn function one time for each element in the array.

▸ (`previousValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentIndex`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *[ExecuteResult](_models_intent_.executeresult.md)*

**Parameters:**

Name | Type |
------ | ------ |
`previousValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentIndex` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

▸ **reduceRight**(`callbackfn`: function, `initialValue`: [ExecuteResult](_models_intent_.executeresult.md)): *[ExecuteResult](_models_intent_.executeresult.md)*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[reduceRight](_models_intent_.executeresults.md#reduceright)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1363

**Parameters:**

▪ **callbackfn**: *function*

▸ (`previousValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentIndex`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *[ExecuteResult](_models_intent_.executeresult.md)*

**Parameters:**

Name | Type |
------ | ------ |
`previousValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentIndex` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪ **initialValue**: *[ExecuteResult](_models_intent_.executeresult.md)*

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

▸ **reduceRight**<**U**>(`callbackfn`: function, `initialValue`: U): *U*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[reduceRight](_models_intent_.executeresults.md#reduceright)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1369

Calls the specified callback function for all the elements in an array, in descending order. The return value of the callback function is the accumulated result, and is provided as an argument in the next call to the callback function.

**Type parameters:**

▪ **U**

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to four arguments. The reduceRight method calls the callbackfn function one time for each element in the array.

▸ (`previousValue`: U, `currentValue`: [ExecuteResult](_models_intent_.executeresult.md), `currentIndex`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *U*

**Parameters:**

Name | Type |
------ | ------ |
`previousValue` | U |
`currentValue` | [ExecuteResult](_models_intent_.executeresult.md) |
`currentIndex` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪ **initialValue**: *U*

If initialValue is specified, it is used as the initial value to start the accumulation. The first call to the callbackfn function provides this value as an argument instead of an array value.

**Returns:** *U*

___

###  reverse

▸ **reverse**(): *[ExecuteResult](_models_intent_.executeresult.md)[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[reverse](_models_intent_.executeresults.md#reverse)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1251

Reverses the elements in an Array.

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)[]*

___

###  shift

▸ **shift**(): *[ExecuteResult](_models_intent_.executeresult.md) | undefined*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[shift](_models_intent_.executeresults.md#shift)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1255

Removes the first element from an array and returns it.

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md) | undefined*

___

###  slice

▸ **slice**(`start?`: undefined | number, `end?`: undefined | number): *[ExecuteResult](_models_intent_.executeresult.md)[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[slice](_models_intent_.executeresults.md#slice)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1261

Returns a section of an array.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`start?` | undefined &#124; number | The beginning of the specified portion of the array. |
`end?` | undefined &#124; number | The end of the specified portion of the array. This is exclusive of the element at the index 'end'.  |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)[]*

___

###  some

▸ **some**(`callbackfn`: function, `thisArg?`: any): *boolean*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[some](_models_intent_.executeresults.md#some)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1319

Determines whether the specified callback function returns true for any element of an array.

**Parameters:**

▪ **callbackfn**: *function*

A function that accepts up to three arguments. The some method calls
the callbackfn function for each element in the array until the callbackfn returns a value
which is coercible to the Boolean value true, or until the end of the array.

▸ (`value`: [ExecuteResult](_models_intent_.executeresult.md), `index`: number, `array`: [ExecuteResult](_models_intent_.executeresult.md)[]): *unknown*

**Parameters:**

Name | Type |
------ | ------ |
`value` | [ExecuteResult](_models_intent_.executeresult.md) |
`index` | number |
`array` | [ExecuteResult](_models_intent_.executeresult.md)[] |

▪`Optional`  **thisArg**: *any*

An object to which the this keyword can refer in the callbackfn function.
If thisArg is omitted, undefined is used as the this value.

**Returns:** *boolean*

___

###  sort

▸ **sort**(`compareFn?`: undefined | function): *this*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[sort](_models_intent_.executeresults.md#sort)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1271

Sorts an array.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`compareFn?` | undefined &#124; function | Function used to determine the order of the elements. It is expected to return a negative value if first argument is less than second argument, zero if they're equal and a positive value otherwise. If omitted, the elements are sorted in ascending, ASCII character order. ```ts [11,2,22,1].sort((a, b) => a - b) ```  |

**Returns:** *this*

___

###  splice

▸ **splice**(`start`: number, `deleteCount?`: undefined | number): *[ExecuteResult](_models_intent_.executeresult.md)[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[splice](_models_intent_.executeresults.md#splice)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1277

Removes elements from an array and, if necessary, inserts new elements in their place, returning the deleted elements.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`start` | number | The zero-based location in the array from which to start removing elements. |
`deleteCount?` | undefined &#124; number | The number of elements to remove.  |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)[]*

▸ **splice**(`start`: number, `deleteCount`: number, ...`items`: [ExecuteResult](_models_intent_.executeresult.md)[]): *[ExecuteResult](_models_intent_.executeresult.md)[]*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[splice](_models_intent_.executeresults.md#splice)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1284

Removes elements from an array and, if necessary, inserts new elements in their place, returning the deleted elements.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`start` | number | The zero-based location in the array from which to start removing elements. |
`deleteCount` | number | The number of elements to remove. |
`...items` | [ExecuteResult](_models_intent_.executeresult.md)[] | Elements to insert into the array in place of the deleted elements.  |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)[]*

___

###  toLocaleString

▸ **toLocaleString**(): *string*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[toLocaleString](_models_intent_.executeresults.md#tolocalestring)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1223

Returns a string representation of an array. The elements are converted to string using their toLocalString methods.

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[toString](_models_intent_.executeresults.md#tostring)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1219

Returns a string representation of an array.

**Returns:** *string*

___

###  unshift

▸ **unshift**(...`items`: [ExecuteResult](_models_intent_.executeresult.md)[]): *number*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[unshift](_models_intent_.executeresults.md#unshift)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1289

Inserts new elements at the start of an array.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`...items` | [ExecuteResult](_models_intent_.executeresult.md)[] | Elements to insert at the start of the Array.  |

**Returns:** *number*

___

###  values

▸ **values**(): *IterableIterator‹[ExecuteResult](_models_intent_.executeresult.md)›*

*Inherited from [ExecuteResults](_models_intent_.executeresults.md).[values](_models_intent_.executeresults.md#values)*

Defined in node_modules/typescript/lib/lib.es2015.iterable.d.ts:75

Returns an iterable of values in the array

**Returns:** *IterableIterator‹[ExecuteResult](_models_intent_.executeresult.md)›*