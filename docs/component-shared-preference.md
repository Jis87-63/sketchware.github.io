---
id: component-shared-preference
title: SharedPreference
sidebar_label: SharedPreference
---

Shared Preference is used to **locally save data on the device**.

## Example

Using setData block to save a value of `someValue` with the key `someKey`.

![example](assets/sharedpreference/example.png)

<br/>

--------------------

# Blocks

## getData

getData is used to retrieve the saved data.

![get data](assets/sharedpreference/get-data.png)

| Type              | Explanation                                 | Required |
| ----------------- | ------------------------------------------- | -------- |
| Shared Preference | Shared Preference Component                 | Yes      |
| String            | Key of the value you are trying to retrieve | Yes      |

## setData

setData is used to save data.

![set data](assets/sharedpreference/set-data.png)

| Type              | Explanation                  | Required |
| ----------------- | ---------------------------- | -------- |
| Shared Preference | Shared Preference Component  | Yes      |
| String            | Key value                    | Yes      |
| String            | Value you are trying to save | Yes      |

## removeData

removeData is used to remove the data with the key value.

![remove data](assets/sharedpreference/remove-data.png)

| Type              | Explanation                               | Required |
| ----------------- | ----------------------------------------- | -------- |
| Shared Preference | Shared Preference Component               | Yes      |
| String            | Key of the value you are trying to delete | Yes      |
