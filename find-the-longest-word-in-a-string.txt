function findLongestWordLength(str) {
  return Math.max(...str.split(" ").map(word => word.length));
}