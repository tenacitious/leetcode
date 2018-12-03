var lengthOfLastWord = function(s) {
    var lastWordLen = 0;
    s = s.trim();
    if (s.indexOf(' ') > -1) {
        var tempArr = s.split(' ');
        lastWordLen = tempArr[tempArr.length - 1].length;
    } else {
        lastWordLen = s.length;
    }
    return lastWordLen;
};
