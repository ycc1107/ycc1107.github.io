---
title: Scala Study 1
---

--- scala 
def insert( x: Int, xs:List[Int]) : List[Int] = {
        case List() => List(x)
        case y::ys => if( x <= y) x::ys else y::insert(x,ys)
    }
---