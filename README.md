### Waiver Statute Extraction & Classification – SOP (Work Completed & Continuation Steps)

Here is the process I used to collect, clean, and organize the waiver statute data.

I started by downloading all waiver documents from the GaDOE link provided (https://lor2.gadoe.org/gadoe/items/268850de-088a-4f22-b8b2-ef9bc3f8c47e/1/). All files were saved locally, and any scripts or tools used will need to have their file paths updated to match wherever the files are stored on your machine.

Next, I ran an OCR process on the documents to extract the text. Because these are scanned PDFs, the OCR is not perfectly accurate. You will notice errors in statute codes, formatting, and occasional misreads in the text. This is expected and requires manual cleanup.

After extraction, I moved the relevant information into Excel. The dataset includes counties, source documents, and extracted statute codes (and in some cases associated text). The structure is already set up, so continue using the same format.

I then manually reviewed the OCR output for each county to clean it. This included correcting statute codes, standardizing formatting (especially variations of “O.C.G.A.”), and removing duplicates or obvious errors.

I created a “Definition” tab in the Excel file during this process. This tab maps statute codes to waiver categories/types. Using this, I manually linked statute codes in the main dataset to their corresponding categories.

For the remaining counties, continue using the same approach: identify the statute code, match it to the Definition tab, and assign the correct category. If a statute is new, add it to the Definition tab before using it. If a statute code consistently maps to a single type, a formula can be used and dragged down to apply the match.

Some statute codes may correspond to different statute types depending on the context in the document. Because of this, you cannot rely entirely on a one-to-one match between statute code and category. For these cases, you will need to manually review the statute in the original document and assign the correct type based on context. Do not assume the same statute code will always map to the same category.

Throughout the process, I used previously categorized statutes as a reference point since many of them repeat across counties. This helps speed up matching and keeps categorization consistent.

Before finishing, do a final quality check. Make sure each statute has a category, there are no obvious OCR errors left, and formatting is consistent across the dataset. If something looks off, refer back to the original document to verify.

