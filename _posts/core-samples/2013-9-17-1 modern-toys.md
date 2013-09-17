layout: page 
title: 1 modern toys
tagline: A Little Java A Few Patterns

##Keyword

type, abstract, class, extends

##Advice

When specifying a collection of data, use abstract classes for datatypes and extended classes for variants. 

##Question

    abstract class Num{
    };

    class Zero extends Num{
    };

    class OneMoreThan extends Num{
    public:
      	Num predecessor;
      	OneMoreThan(Num _p){
	     predecessor = _p;
	}};

   
   按照以上定义，理解：
   new OneMoreThan(
	     new OneMoreThan(
	         new OneMoreThan(
		       new OneMoreThan(
			         new Zero()))));
