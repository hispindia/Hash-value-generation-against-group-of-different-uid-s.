# Hash-value-generation-against-group-of-different-uid-s.
Hash value generation against group of different uid's.

Function to generate Hash(MD5) of fixed length limited to 11 characters for any number of UIDS in any order.

Output will always be same for all UIDS passed in any order!

Sample output for following 2 arrays:

var dhisUids = ["VG82v0dFGeP", "u3hqApNr5tE", "nTkJpWTP5B0", "WP6uQBzHU1o"];
var dhisUidsRandom = ["u3hqApNr5tE", "VG82v0dFGeP", "WP6uQBzHU1o", "nTkJpWTP5B0"];


output for dhisUids: 1cc30fd0a35
output for dhisUidsRandom: 1cc30fd0a35




