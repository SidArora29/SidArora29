# Setup

Copy the contents of this pack into the `SidArora29/SidArora29` profile repository.

In **Settings → Actions → General → Workflow permissions**, select **Read and write permissions**.

Then open **Actions** and manually run:

1. Update GitHub Profile Analytics
2. Update Contribution Activity
3. Update Contribution Snake

After the first successful runs, all analytics images referenced by `README.md` will exist in the repository/output branch and the broken-image problem will be gone.

The analytics cards are generated as repository SVGs rather than relying on the public Vercel stats/trophy endpoints.
