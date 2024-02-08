# Chess

#   ____ _                      ____                      
#  / ___| |__   ___  ___ ___   / ___| __ _ _ __ ___   ___ 
# | |   | '_ \ / _ \/ __/ __| | |  _ / _` | '_ ` _ \ / _ \
# | |___| | | |  __/\__ \__ \ | |_| | (_| | | | | | |  __/
#  \____|_| |_|\___||___/___/  \____|\__,_|_| |_| |_|\___|

A four-player chess game playable in any browser using jQuery and websockets.

loc is a 2D array that contains the coordinates of each box.

piece is a 2D array that contains an integer 0-6 which represents chess pieces:

0=empty
1=pawn
2=rook
3=knight
4=bishop
5=queen
6=king

Each box has it's own CSS div named #divX, with the X being the "box number".