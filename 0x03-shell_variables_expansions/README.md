lias ls="rm *"i
echo "hello "$USER
PATH=$PATH:/action
echo $PATH | tr ':' '\n' | wc -l
printenv
set
BETTY="Holberton"
export HOLBERTON="Betty"
echo $(( 128 + $TRUEKNOWLEDGE ))
echo $(( $POWER / $DIVIDE ))
echo $(( BREATH**LOVE ))
echo $(( 2#$BINARY ))
echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo"
printf '%.2f\n' $NUM
printf '%x\n' $DECIMAL
tr 'A-Za-z' 'N-ZA-Mn-za-m'
paste - - | cut -f1i
printf '%o\n' $(( $((5#$(echo $STIR | tr 'stir.' '01234'))) + $((5#$(echo $WATER | tr 'water' '01234'))) )) | tr '01234567' 'bestchol'
