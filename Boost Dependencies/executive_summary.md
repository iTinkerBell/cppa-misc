# Boost Dependency Executive Summary

**Generated:** 2025-10-24 11:53:13

---

## 1. Overall Statistics

### Module Dependencies

| Metric | Value |
|--------|-------|
| Total Modules | 152 |
| Total Dependencies | 2764 |
| Primary Dependencies | 1381 |

### Header Dependencies

| Metric | Value |
|--------|-------|
| Total Headers | 7741 |
| Total Dependencies | 40446 |
| Primary Dependencies | 20223 |

---

## 2. Module Rankings by Dependencies

### Top 5 and Bottom 5 Modules by All Dependencies

| Rank | Module | Primary Dependencies | All Dependencies | Primary Dependents | All Dependents |
|------|--------|---------------------|------------------|-------------------|----------------|
| 1 | numeric~odeint | 19 | 83 | 0 | 0 |
| 2 | graph_parallel | 26 | 77 | 0 | 0 |
| 3 | property_map_parallel | 13 | 74 | 1 | 1 |
| 4 | mpi | 18 | 73 | 3 | 3 |
| 5 | parameter_python | 4 | 73 | 0 | 0 |
| ... | ... | ... | ... | ... | ... |
| 148 | callable_traits | 0 | 0 | 1 | 1 |
| 149 | ratio | 0 | 0 | 1 | 27 |
| 150 | (unknown) | 0 | 0 | 7 | 48 |
| 151 | qvm | 0 | 0 | 1 | 1 |
| 152 | pfr | 0 | 0 | 1 | 1 |

---

## 3. Module Rankings by Dependents

### Top 5 and Bottom 5 Modules by All Dependents

| Rank | Module | Primary Dependencies | All Dependencies | Primary Dependents | All Dependents |
|------|--------|---------------------|------------------|-------------------|----------------|
| 1 | config | 0 | 0 | 137 | 141 |
| 2 | assert | 1 | 1 | 94 | 129 |
| 3 | throw_exception | 2 | 2 | 69 | 122 |
| 4 | static_assert | 1 | 1 | 59 | 121 |
| 5 | core | 4 | 4 | 98 | 115 |
| ... | ... | ... | ... | ... | ... |
| 148 | nowide | 2 | 33 | 0 | 0 |
| 149 | sort | 5 | 31 | 0 | 0 |
| 150 | timer | 3 | 3 | 0 | 0 |
| 151 | yap | 3 | 24 | 0 | 0 |
| 152 | parameter_python | 4 | 73 | 0 | 0 |

---

## 4. Header Rankings by Dependencies

### Top 5 and Bottom 5 Headers by All Dependencies

| Rank | Header | Primary Dependencies | All Dependencies | Primary Dependents | All Dependents |
|------|--------|---------------------|------------------|-------------------|----------------|
| 1 | boost/graph/distributed/strong_components.hpp | 12 | 130 | 0 | 0 |
| 2 | boost/graph/distributed/adjacency_list.hpp | 20 | 122 | 0 | 0 |
| 3 | boost/graph/distributed/betweenness_centrality.hpp | 12 | 118 | 0 | 0 |
| 4 | boost/graph/distributed/compressed_sparse_row_graph.hpp | 6 | 113 | 0 | 0 |
| 5 | boost/log/expressions/formatters/char_decorator.hpp | 20 | 113 | 0 | 0 |
| ... | ... | ... | ... | ... | ... |
| 7737 | boost/spirit/fusion/sequence/as_fusion_sequence.hpp | 0 | 0 | 1 | 1 |
| 7738 | boost/spirit/fusion/sequence/begin.hpp | 0 | 0 | 2 | 2 |
| 7739 | boost/spirit/fusion/sequence/cons.hpp | 0 | 0 | 1 | 1 |
| 7740 | boost/spirit/fusion/sequence/detail/sequence_base.hpp | 0 | 0 | 1 | 1 |
| 7741 | boost/spirit/fusion/sequence/end.hpp | 0 | 0 | 2 | 2 |

---

## 5. Header Rankings by Dependents

### Top 5 and Bottom 5 Headers by All Dependents

| Rank | Header | Primary Dependencies | All Dependencies | Primary Dependents | All Dependents |
|------|--------|---------------------|------------------|-------------------|----------------|
| 1 | boost/config.hpp | 0 | 0 | 2145 | 4690 |
| 2 | boost/detail/workaround.hpp | 0 | 0 | 276 | 1775 |
| 3 | boost/config/workaround.hpp | 0 | 0 | 99 | 1438 |
| 4 | boost/assert.hpp | 1 | 1 | 792 | 1247 |
| 5 | boost/static_assert.hpp | 2 | 2 | 327 | 1131 |
| ... | ... | ... | ... | ... | ... |
| 7737 | boost/process/v1/detail/windows/show_window.hpp | 2 | 2 | 0 | 0 |
| 7738 | boost/process/v1/detail/windows/wait_for_exit.hpp | 2 | 2 | 0 | 0 |
| 7739 | boost/redis/response.hpp | 1 | 1 | 0 | 0 |
| 7740 | boost/wave/grammars/cpp_predef_macros_gen.hpp | 1 | 1 | 0 | 0 |
| 7741 | boost/wave/util/pattern_parser.hpp | 1 | 1 | 0 | 0 |

---

## 6. Module Merge Recommendations

### Top 10 2-Module Merge Recommendations

| Rank | Modules | Original Edges | Merged Edges | Edge Reduction | Reduction % |
|------|---------|----------------|--------------|----------------|-------------|
| 1 | config + core | 239 | 137 | 102 | 42.7% |
| 2 | assert + throw_exception | 166 | 102 | 64 | 38.6% |
| 3 | mpl + type_traits | 145 | 90 | 55 | 37.9% |
| 4 | iterator + static_assert | 107 | 74 | 33 | 30.8% |
| 5 | preprocessor + utility | 91 | 65 | 26 | 28.6% |
| 6 | graph + range | 85 | 60 | 25 | 29.4% |
| 7 | serialization + spirit | 70 | 48 | 22 | 31.4% |
| 8 | function + smart_ptr | 67 | 46 | 21 | 31.3% |
| 9 | compute + xpressive | 55 | 37 | 18 | 32.7% |
| 10 | fusion + proto | 44 | 28 | 16 | 36.4% |

### Top 10 3-Module Merge Recommendations

| Rank | Modules | Original Edges | Merged Edges | Edge Reduction | Reduction % |
|------|---------|----------------|--------------|----------------|-------------|
| 1 | assert + config + core | 334 | 137 | 197 | 59.0% |
| 2 | mpl + static_assert + type_traits | 205 | 95 | 110 | 53.7% |
| 3 | graph + iterator + throw_exception | 164 | 99 | 65 | 39.6% |
| 4 | preprocessor + smart_ptr + utility | 131 | 77 | 54 | 41.2% |
| 5 | range + serialization + spirit | 109 | 62 | 47 | 43.1% |
| 6 | compute + fusion + thread | 92 | 56 | 36 | 39.1% |
| 7 | bind + function + optional | 74 | 42 | 32 | 43.2% |
| 8 | mpi + property_map + python | 63 | 31 | 32 | 50.8% |
| 9 | multi_index + property_tree + xpressive | 63 | 35 | 28 | 44.4% |
| 10 | integer + random + variant | 61 | 35 | 26 | 42.6% |

---

*End of Executive Summary*
