# Updated Version

- Filtering out of empty and less than 32 bytes data field before clustering  
- New, updated cycle status (after most of recent jadelfake drops)

The error due to the empty messages was not present in DCCT data, data that was sent out to the devs days ago.  
That error of mine was detected quite quickly, since dcct cluster was merged with the large one.  
This was responsible for the dropped verifiers from the cluster, question 3 from the devs.

I told most of the technical users about the error and its cause, but since it didn't change the 50%+ outcome, I did not hurry to post it.  
I was expecting more users would really analyse the data, find that error and show they did their job toroughly.  
(so far, no other user did release an analysis nor a denial of that analysis)

I also got confirmation from qTrade that their deposit IDs are globally unique and never reused.

## Stats  

With the updated data and new cycle, the largest cluster consists of 1758 addresses, 1406 of them being in-cycle.  
The cycle at that time was 2759, which makes 50.96% for the cluster.

Total Nyzo sent to qTrade by these addresses is 6,447,737.03022 Nyzos.  

Since recently joined verifiers did not sent to qTrade yet, they are excluded from the clustering.  
This 50.96% therefore is a minimum.

## group_joins_by_block.png

From dcct:

```
Joins of this groups verifier vs other joins
(by block)
most recent joins are not tracked as most have no qtrade deposits yet
They started early, and had >50% of all joins for quite a while
I grouped 200k blocks for each data point
```
