# Copyright The OpenTelemetry Authors
# SPDX-License-Identifier: Apache-2.0

add_library(common_metrics_foo_library foo_library.h foo_library.cc)
target_link_libraries(common_metrics_foo_library PUBLIC opentelemetry_api)
