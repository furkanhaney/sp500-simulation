# SP500 Simulation with a Normal Distribution

![](/readme/simulated.png)

The distribution of the daily price changes of a security can be modeled as randomly sampled from a probability distribution.

This notebook imagines a possible path for SP500 into the future by fitting a Normal Distribution to the change in daily prices and iteratively sampling. Note that every run will give a different projection.

## Intuition

A look at the data shows that Normal distribution can be a good starting point for this investigation despite its weaknesses.

![](/readme/distribution.png)

## Limitations

This model makes unrealistic assumptions not limited to:

- Annual price changes are i.i.d.
- Returns stay the same long-term.
- The underlying distribution is normal.

## License

MIT License
