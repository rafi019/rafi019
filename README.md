//
//  main.swift
//  homework 2.1
//
//  Created by Raffi on 23.04.22.
//

import Foundation


//  homework 2.1

var a : Int = 5, b : Int = 145, c : Float = -1234.33, d : Bool = false
(a = -a)
(b = -b)
(c = -c)
(d = !d)
print("a = \(a) b = \(b) c = \(c) d = \(d)")
 
// homework 2.2

let isTen : Bool = false
print("isTen = \(isTen ? "45" : "10")")

// homework2.3

let isGirl : Bool = false
let person = ( isGirl ? "isGirl" : "isBoy")
print("person = \(person)")

// homework 2.4

let a1 : Float = 35.7
let b1 : Float = 47.67
let max = ( a1 > b1 ? a1 : b1)
print("max = \(max)")

// homework 2.5

let a2 : Float = 35.7
let b2 : Float = 47.67
let min = ( a2 < b2 ? a2 : b2)
print("min = \(min)")

// homework 2.6

let a3 : Int = 3
let b3: Int = 1096
let c3 : Int = 36
let max3 = a3 > b3 ? ( a3 > c3 ? a3 : c3) : ( b3 > c3 ? b3 : c3)
print("max = \(max3)")



// homework 2.7

let a4 : Int = 3
let b4 : Int = 1096
let c4 : Int = -36
var min4 = a4 < b4 ? (a4 < c4 ? a4 : c4 ) :  ( b4 < c4 ? b4 : c4)
print("min = \(min4)")


// homework 2.8

var strEmpty = ""
print("strIsEmpty = \(strEmpty.isEmpty), strEmpty = \(strEmpty)")

// homework 2.9

let str1 : String = "Hello"
let str1Count = str1.count
print("str1Count = \(str1Count)")

// homework 2.13

var str3 : String = "Hello"
let stri : String = "GITC"
str3 = str3 + stri
str3 += stri
str3.append(stri)
print(str3)

// homework 2.12

let str4 : String = "Hello"
print("startIndex= \(str4[str4.startIndex])")

// homework 2.13

let str5 : String = "Hello"

print("str5EndIndex = \(str5[str5.index(before : str5.endIndex)])")

// homework 2.14

var str6 : String = "Hello"
let offset = str6.index(str6.startIndex, offsetBy: 2)
print("str6 = \(str6[offset])")

// homework 2.15

var str7 : String = "Hello"
str7.insert(")", at: str7.startIndex)
print("str7 = \( str7)")

//homework 2.16

var str8 : String = "Hello"
str8.insert("-", at: str8.index(after: str8.startIndex))
print("str8 = \(str8)")

//homework 2.17

var str9 : String = "Hello"
str9.insert(contentsOf: "-Error-", at: str9.index(after: str9.startIndex))
print("str9 = \(str9)")
  
// homework 2.18

var str10 : String = "Hello"
str10.remove(at: str10.startIndex)
print("str10 = \(str10)")

//homework 2.19

var str11 : String = "Hello"
str11.remove(at: str11.index(before: str11.endIndex))
print(str11)

//homework 2.20

var str12 : String = "Hello"
str12.remove(at: str11.index(str12.startIndex, offsetBy: 2))
print("str12 = \(str12)")

