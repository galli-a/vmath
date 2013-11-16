# `vmath`

Copy of the `vmath.vim` plugin by Damian Conway, to do math on a column of numbers

## Usage

Create mappings, for example

    vmap <expr>  ++  VMATH_YankAndAnalyse() 
	nmap         ++  vip++

Type a column of numbers, then use the mappings. Once you have computed the sum, it is available in the default yank buffer, and also in the `"s` buffer. The average is available in the `"a` buffer, the minimum in the `"n` buffer, the maximum in the `"x` buffer and the min-to-max range in the `"r` buffer.
