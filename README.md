
# date-fns-holiday-my

The purpose of this project is to give an interface to work with holidays using `date-fns`
Inspired from [date-fns-holiday-us](https://github.com/jonstuebe/date-fns-holiday-us)

## Install

```
yarn add date-fns-holiday-my date-fns
```

or with npm:

```
npm i date-fns-holiday-my date-fns
```

## API

### Type aliases

* [Holiday](README.md#holiday)
* [Holidays](README.md#holidays)

### Functions

* [getChristmas](README.md#getchristmas)
* [getLaborDay](README.md#getlaborday)
* [getNewYearsDay](README.md#getnewyearsday)


## Type aliases

###  Holiday

Ƭ **Holiday**: *"christmas" | "easter" | "halloween" | "valentinesDay" | "mothersDay" | "columbusDay" | "independenceDay" | "presidentsDay" | "laborDay" | "veteransDay" | "thanksgiving" | "newYearsEve" | "martinLutherKingJrDay" | "newYearsDay" | "fathersDay" | "memorialDay" | "goodFriday" | "juneteenth"*

*Defined in [index.ts:13](https://github.com/jonstuebe/date-fns-holiday-us/blob/master/src/index.ts#L13)*

___

###  Holidays

Ƭ **Holidays**: *object*

*Defined in [index.ts:139](https://github.com/jonstuebe/date-fns-holiday-us/blob/master/src/index.ts#L139)*

#### Type declaration:

## Functions

###  getChristmas

▸ **getChristmas**(`year`: number): *Date*

*Defined in [index.ts:99](https://github.com/jonstuebe/date-fns-holiday-us/blob/master/src/index.ts#L99)*

**Parameters:**

Name | Type |
------ | ------ |
`year` | number |

**Returns:** *Date*


___

###  getHolidays

▸ **getHolidays**(`year`: number): *[Holidays](README.md#holidays)*

*Defined in [index.ts:147](https://github.com/jonstuebe/date-fns-holiday-us/blob/master/src/index.ts#L147)*

**Parameters:**

Name | Type |
------ | ------ |
`year` | number |

**Returns:** *[Holidays](README.md#holidays)*

___

###  getLaborDay

▸ **getLaborDay**(`year`: number): *Date*

*Defined in [index.ts:103](https://github.com/jonstuebe/date-fns-holiday-us/blob/master/src/index.ts#L103)*

**Parameters:**

Name | Type |
------ | ------ |
`year` | number |

**Returns:** *Date*

___


###  getNewYearsDay

▸ **getNewYearsDay**(`year`: number): *Date*

*Defined in [index.ts:123](https://github.com/jonstuebe/date-fns-holiday-us/blob/master/src/index.ts#L123)*

**Parameters:**

Name | Type |
------ | ------ |
`year` | number |

**Returns:** *Date*

___

