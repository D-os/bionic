# Copyright (C) 2022 The Android Open Source Project
# All rights reserved.
#
# Redistribution and use in source and binary forms, with or without
# modification, are permitted provided that the following conditions
# are met:
#  * Redistributions of source code must retain the above copyright
#    notice, this list of conditions and the following disclaimer.
#  * Redistributions in binary form must reproduce the above copyright
#    notice, this list of conditions and the following disclaimer in
#    the documentation and/or other materials provided with the
#    distribution.
#
# THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
# "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
# LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
# FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
# COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
# INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
# BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS
# OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED
# AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
# OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT
# OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
# SUCH DAMAGE.

load("//build/bazel/rules/apis:cc_api_contribution.bzl", "cc_api_headers")

package(default_visibility = ["//bionic/libc:__pkg__"])

cc_api_headers(
  name="libc_kernel_uapi_headers",
  hdrs=glob(["**/*.h"]),
  system=True,
)

cc_api_headers(
  name="libc_kernal_uapi_asm_arm_headers",
  include_dir="asm-arm",
  hdrs=glob(["asm-arm/**/*.h"]),
  system=True,
  arch="arm",
)

cc_api_headers(
  name="libc_kernal_uapi_asm_arm64_headers",
  include_dir="asm-arm64",
  hdrs=glob(["asm-arm64/**/*.h"]),
  system=True,
  arch="arm64",
)

cc_api_headers(
  name="libc_kernal_uapi_asm_x86_headers",
  include_dir="asm-x86",
  hdrs=glob(["asm-x86/**/*.h"]),
  system=True,
  arch="x86",
)

cc_api_headers(
  name="libc_kernal_uapi_asm_x86_64_headers",
  include_dir="asm-x86_64",
  hdrs=glob(["asm-x86_64/**/*.h"]),
  system=True,
  arch="x86_64",
)
