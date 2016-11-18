# primes

/// generate primes in c

/// large values may be computationally intensive

/// monitor run machine's sensors:

/// In BASH $ __=`sensors | grep Core` && echo \(`echo $__ | sed 's/.*+\(.*\).C\(\s\)\+(.*/\1/g' | tr "\n" "+" | head -c-1`\)\/`echo $__ | wc -l` | bc && unset __

/// Glances https://nicolargo.github.io/glances/ 


/// gcc 

gcc -Wall primes.c -o primes   /// -m32 or -m64 bit switch

$chmod u+x primes

$./primes

/// more on prime numbers

http://mathworld.wolfram.com/PrimeNumber.html

http://mathworld.wolfram.com/PrimeFormulas.html

http://mathworld.wolfram.com/RiemannHypothesis.html





