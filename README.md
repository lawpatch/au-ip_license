# Intellectual Property Licence (Australia)

### Purpose

The language in this repo licenses intellectual property rights in **Australian** legal agreements.

The example below assumes the use of the LawPatch clause <a href="https://github.com/lawpatch/lawpatch-docs" target="_blank">here</a>.

### Simple Licences with LawPatch

Licensing intellectual property is a technical area.  If you want to draft a licence and make its characteristics clear, you end up with a lot of formulaic language.  

With a LawPatch intellectual property licence, the default approach is a permissive license.  The reason we've taken this approach is that, in our transactional experience, parties tend to discuss restrictions.  With a default permissive position, the restrictions are highlighted.

If you want your license to be irrevocable, perpetual, transferable, sub-licenceable, non-exclusive, royalty free and global, you just need to write:

> Provider grants an <a href="" target="_blank">expansive licence</a> to the Customer in relation to the Code for any purpose.

Simple.

If you want your licence to be **non-transferable**, **exclusive** and applicable **only in Australia** (but expansive in every other way), you just need to write:

> Provider grants an exclusive, non-transferable <a href="" target="_blank">licence</a> to the Customer to deal with the Code in Australia for any purpose.

### Parameters

The language in this repo is *not* language that you can import wholesale with a simple incorporation by reference - it assumes that you have included certain information in the clause that imports it (the `Exception` parameter is optional).

The parameters for this patch are:

- `Licensor` - The party licensing the intellectual property;
- `Licensee` - The party receiving the licence of the intellectual property;
- `Subject` - The intellectual property that is licensed (the more specific the description the better);
- `Purpose` - the purpose that the Licensor will allow the subject intellectual property to be used for;
- `Restrictions` (optional) - one or many of the following can be used:
    - revocable;
    - limited term;
    - non-transferrable;
    - non-subliceneable;
    - exclusive;
    - royalties due; and
    - confined to a territory,
- `Exception` (optional) - An exception to the licence.

### Not Legal Advice

This is not legal advice.  Lawyers are involved in producing these terms, but they obviously aren't familiar with your circumstances.  Speak to your lawyer to make sure that the language is well aligned with your circumstances.

### Licence

The language in this repo is released under the license in `license.md`.
