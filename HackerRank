function breakingRecords(scores) {
    let low = 0;
    let high = 0;
    let valuehigh = scores[0];
    let valuelow = scores[0];

    for (let i = 1; i <= scores.length; i++) {
        if (scores[i] > valuehigh) {
            valuehigh = scores[i];
            high++;
        }
        if (scores[i] < valuelow) {
            valuelow = scores[i];
            low++;
        }     
    }
    return[high, low];
}
