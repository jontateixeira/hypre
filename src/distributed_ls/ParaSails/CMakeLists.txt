# Copyright 1998-2019 Lawrence Livermore National Security, LLC and other
# HYPRE Project Developers. See the top-level COPYRIGHT file for details.
#
# SPDX-License-Identifier: (Apache-2.0 OR MIT)

target_sources(HYPRE
  PRIVATE
  ConjGrad.c
  DiagScale.c
  FGmres.c
  Hash.c
  hypre_ParaSails.c
  LoadBal.c
  Matrix.c
  Mem.c
  Numbering.c
  OrderStat.c
  ParaSails.c
  PrunedRows.c
  RowPatt.c
  StoredRows.c
)
