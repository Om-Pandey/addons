licenses(["notice"])  # Apache 2.0

package(default_visibility = ["//visibility:public"])

py_library(
    name = "metrics",
    srcs = [
        "__init__.py",
        "cohens_kappa.py",
        "f_scores.py",
        "hamming.py",
        "matthews_correlation_coefficient.py",
        "multilabel_confusion_matrix.py",
        "r_square.py",
        "utils.py",
    ],
    deps = [
        "//tensorflow_addons/utils",
    ],
)

py_test(
    name = "cohens_kappa_test",
    size = "small",
    srcs = [
        "cohens_kappa_test.py",
    ],
    main = "cohens_kappa_test.py",
    deps = [
        ":metrics",
    ],
)

py_test(
    name = "r_square_test",
    size = "small",
    srcs = [
        "r_square_test.py",
    ],
    main = "r_square_test.py",
    deps = [
        ":metrics",
    ],
)

py_test(
    name = "f_test",
    size = "small",
    srcs = [
        "f_test.py",
    ],
    main = "f_test.py",
    deps = [
        ":metrics",
    ],
)

py_test(
    name = "multilabel_confusion_matrix_test",
    size = "small",
    srcs = [
        "multilabel_confusion_matrix_test.py",
    ],
    main = "multilabel_confusion_matrix_test.py",
    deps = [
        ":metrics",
    ],
)

py_test(
    name = "matthews_correlation_coefficient_test",
    size = "small",
    srcs = [
        "matthews_correlation_coefficient_test.py",
    ],
    main = "matthews_correlation_coefficient_test.py",
    deps = [
        ":metrics",
    ],
)

py_test(
    name = "hamming_test",
    size = "small",
    srcs = [
        "hamming_test.py",
    ],
    main = "hamming_test.py",
    deps = [
        ":metrics",
    ],
)
