# Intellectual Property Licence (Australia)

### Purpose

The language in this repo is language to license intellectual property in **Australian** legal agreements.

The examples assume the use of the LawPatch description clause <a href="https://github.com/lawpatch/lawpatch-docs" target="_blank">here</a>.

### Simple Licences with LawPatch

Licensing intellectual property is a technical area.  If you want to draft a licence and make its characteristics clear, you end up with a lot of formulaic language.  Unless specified otherwise, a LawPatch licence characteristics are by default expansive.

If you want your license to be irrevocable, transferable, sub-licenceable, non-exclusive, royaly free and global, you just need to write:

> Provider grants a <a href="" target="_blank">licence</a> to the Customer in relation to the Code.

Simple.

If you want your licence to be **non-transferable** and exclusive (and expansive in every other way), you just need to write:

> Provider grants an exclusive, non-transferable <a href="" target="_blank">licence</a> to the Customer in relation to the Code.

### Parameters

The language in this repo is *not* language that you can import wholesale with a simple incorporation by reference - it assumes that you have included certain information in the clause that imports it (the `Exception` parameter is optional).

The parameters for this patch are:

- `Licensor` - The party transferring ownership of the intellectual property;
- `Licensee` - The party recieving the ownership of the intellectual property;
- `Subject` - The intellectual property that is licensed (the more specific the better); 
- `Purpose` - the purpose that the Licensor will allow the subject intellectual property to be used;
- `Restrictions` (optional), one or many):
    - revocable;
    - limited term;
    - non-transferrable;
    - non-subliceneable;
    - exclusive;
    - royalty paying;
    - confined to a territory; and
    - {unlimited}.
- `Exception` (optional) - An exception to the licence.
opposite is “limited term”

### Not Legal Advice

This is not legal advice.  Lawyers are involved in producing these terms, but they obviously aren't familiar with your circumstances.  Speak to your lawyer to make sure that the limitation language is well aligned with your circumstances.

### Licence

The intellectual property licence language is released under the license in `license.md`.
