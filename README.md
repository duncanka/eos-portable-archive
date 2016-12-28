# EOS Portable Boost Binary Archive

This project is a Git clone of the Subversion repository for the EOS Portable Archive project. I am reposting it here for easy inclusion as a submodule in Git projects. The repository was copied from https://epa.svn.codeplex.com/svn using `git-svn`.

The following text is taken from the original project's [CodePlex site](https://epa.codeplex.com/).

## Project Description

**This C++ project provides a portable binary archive to be used with `boost::serialization`.**

When using boost::serialization to make C++ data structures persistent you have different options for for the storage format. The library provides you with different archives to be used together with the serialization framework, you will find XML, ASCII and a binary implementation. The thing about the binary archive is that it was designed for optimal speed and not for portability across different platforms. This is where the EOS portable archive fills the gap, bringing both execution speed and a platform independent space-efficient binary packing.

## Project History

The archive was created at EOS for its projects and first published on boost vault. The code is designed to work as header-only addition to boost starting with version 1.33.1. We provide full backwards compatibility to prior releases and with most features also forward compatibility was achieved since the data format itself did not change.

This code is production quality and has been used in industrial applications for years. Thanks to EOS for providing me the opportunity to publish my work. I feel that it could be of use to many people out there and would appreciate if you dropped a line about your use case and experience.

## Project License

With publication on codeplex the license has changed to MIT license, which is very close to the boost software license.

Last edited Jul 13, 2012 at 4:11 AM by [pfligersdorffer](https://www.codeplex.com/site/users/view/pfligersdorffer), version 5
