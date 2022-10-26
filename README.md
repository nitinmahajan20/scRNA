# scRNA

Recent advancements in next-generation sequencing (NGS) technologies have made single-cell sequencing an increasingly powerful tool for understanding the biology and cellular function, disease diagnosis, therapy response prediction, and treatment selection. Historically, sequencing technology only enabled an average analysis of a total cell population (Bulk RNA-Seq). In contrast, today, tens of thousands of individual cells from a single tissue sample or patient can be analyzed, giving researchers an unprecedented opportunity to understand individual cell populations and their behavior in diseased tissue. RNA-sequencing (RNA-seq) is a genomic approach for detecting and quantifying messenger RNA (mRNA) molecules in biological samples and is helpful in exploring cellular responses. Majorly there are two RNA sequencing - bulk RNA and single single-cell (scRNASeq). The advantage of scRNASeq is to identify and discover the rare populations and mutations which is helpful to understanding cancer, cardiac disorders. Identifying different and new cell populations is important for developing new therapy and diagnosis. However, analyzing the large volumes of data generated from these experiments requires specialized statistical and computational methods. We will use the data from 10X genomics and identify the different cell type clusters based on the expression of different genes. Cells will be treated as rows (samples), and gene expression will be as columns (Variables). This white paper describes the single cell RNA- Seq data analysis for identifying different cell populations in normal human peripheral blood mononuclear cells (PBMCs) using R based platform Seurat. 
