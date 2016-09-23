# <a href="https://lodash.com/">lodash</a> <span>v4.16.1</span>

熟悉Lodash-4.16.1　
顺带做下中文翻译



<!-- div class="toc-container" -->

<!-- div -->

## `Array`
* <a href="#_chunkarray-size1">`_.chunk－－－－－指定长度切割数组`</a>
* <a href="#_compactarray">`_.compact－－－－－数组过滤`</a>
* <a href="#_concatarray-values">`_.concat－－－－－－数组合并`</a>
* <a href="#_differencearray-values">`_.difference－－－－－Ａ与Ｂ做对比，取出Ａ数组中的不同部分`</a>
* <a href="#_differencebyarray-values-iteratee_identity">`_.differenceBy－－－－－两个数组按照指定方式比较`</a>
* <a href="#_differencewitharray-values-comparator">`_.differenceWith－－－－－包含对象的两个数组按照指定方法比较`</a>
* <a href="#_droparray-n1">`_.drop－－－－－从开始位置剔除掉指定位置的元素`</a>
* <a href="#_droprightarray-n1">`_.dropRight－－－－－从最后位置倒序剔除掉指定位置的元素`</a>
* <a href="#_droprightwhilearray-predicate_identity">`_.dropRightWhile－－－－－按照指定的方法剔除元素`</a>
* <a href="#_dropwhilearray-predicate_identity">`_.dropWhile－－－－－－－－－－按照指定的方法剔除元素`</a>
* <a href="#_fillarray-value-start0-endarraylength">`_.fill－－－－－用指定字符从开始位置替换到结束位置`</a>
* <a href="#_findindexarray-predicate_identity-fromindex0">`_.findIndex－－－－－`</a>
* <a href="#_findlastindexarray-predicate_identity-fromindexarraylength-1">`_.findLastIndex－－－－－`</a>
* <a href="#_headarray" class="alias">`_.first` -> `head－－－－－`</a>
* <a href="#_flattenarray">`_.flatten－－－－－`</a>
* <a href="#_flattendeeparray">`_.flattenDeep－－－－－`</a>
* <a href="#_flattendeptharray-depth1">`_.flattenDepth－－－－－`</a>
* <a href="#_frompairspairs">`_.fromPairs－－－－－`</a>
* <a href="#_headarray">`_.head－－－－－`</a>
* <a href="#_indexofarray-value-fromindex0">`_.indexOf－－－－－`</a>
* <a href="#_initialarray">`_.initial－－－－－－－－－－`</a>
* <a href="#_intersectionarrays">`_.intersection－－－－－`</a>
* <a href="#_intersectionbyarrays-iteratee_identity">`_.intersectionBy－－－－－`</a>
* <a href="#_intersectionwitharrays-comparator">`_.intersectionWith－－－－－`</a>
* <a href="#_joinarray-separator-">`_.join－－－－－`</a>
* <a href="#_lastarray">`_.last－－－－－`</a>
* <a href="#_lastindexofarray-value-fromindexarraylength-1">`_.lastIndexOf－－－－－`</a>
* <a href="#_ntharray-n0">`_.nth－－－－－`</a>
* <a href="#_pullarray-values">`_.pull－－－－－`</a>
* <a href="#_pullallarray-values">`_.pullAll－－－－－`</a>
* <a href="#_pullallbyarray-values-iteratee_identity">`_.pullAllBy－－－－－`</a>
* <a href="#_pullallwitharray-values-comparator">`_.pullAllWith－－－－－`</a>
* <a href="#_pullatarray-indexes">`_.pullAt－－－－－`</a>
* <a href="#_removearray-predicate_identity">`_.remove－－－－－`</a>
* <a href="#_reversearray">`_.reverse－－－－－`</a>
* <a href="#_slicearray-start0-endarraylength">`_.slice－－－－－`</a>
* <a href="#_sortedindexarray-value">`_.sortedIndex－－－－－`</a>
* <a href="#_sortedindexbyarray-value-iteratee_identity">`_.sortedIndexBy－－－－－`</a>
* <a href="#_sortedindexofarray-value">`_.sortedIndexOf－－－－－`</a>
* <a href="#_sortedlastindexarray-value">`_.sortedLastIndex－－－－－`</a>
* <a href="#_sortedlastindexbyarray-value-iteratee_identity">`_.sortedLastIndexBy－－－－－`</a>
* <a href="#_sortedlastindexofarray-value">`_.sortedLastIndexOf－－－－－`</a>
* <a href="#_sorteduniqarray">`_.sortedUniq－－－－－`</a>
* <a href="#_sorteduniqbyarray-iteratee">`_.sortedUniqBy－－－－－`</a>
* <a href="#_tailarray">`_.tail－－－－－`</a>
* <a href="#_takearray-n1">`_.take－－－－－`</a>
* <a href="#_takerightarray-n1">`_.takeRight－－－－－`</a>
* <a href="#_takerightwhilearray-predicate_identity">`_.takeRightWhile－－－－－`</a>
* <a href="#_takewhilearray-predicate_identity">`_.takeWhile－－－－－`</a>
* <a href="#_unionarrays">`_.union－－－－－`</a>
* <a href="#_unionbyarrays-iteratee_identity">`_.unionBy－－－－－`</a>
* <a href="#_unionwitharrays-comparator">`_.unionWith－－－－－`</a>
* <a href="#_uniqarray">`_.uniq－－－－－`</a>
* <a href="#_uniqbyarray-iteratee_identity">`_.uniqBy－－－－－`</a>
* <a href="#_uniqwitharray-comparator">`_.uniqWith－－－－－`</a>
* <a href="#_unziparray">`_.unzip－－－－－`</a>
* <a href="#_unzipwitharray-iteratee_identity">`_.unzipWith－－－－－`</a>
* <a href="#_withoutarray-values">`_.without－－－－－`</a>
* <a href="#_xorarrays">`_.xor－－－－－`</a>
* <a href="#_xorbyarrays-iteratee_identity">`_.xorBy－－－－－`</a>
* <a href="#_xorwitharrays-comparator">`_.xorWith－－－－－`</a>
* <a href="#_ziparrays">`_.zip－－－－－`</a>
* <a href="#_zipobjectprops-values">`_.zipObject－－－－－`</a>
* <a href="#_zipobjectdeepprops-values">`_.zipObjectDeep－－－－－`</a>
* <a href="#_zipwitharrays-iteratee_identity">`_.zipWith－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Collection`
* <a href="#_countbycollection-iteratee_identity">`_.countBy－－－－－`</a>
* <a href="#_foreachcollection-iteratee_identity" class="alias">`_.each` -> `forEach－－－－－`</a>
* <a href="#_foreachrightcollection-iteratee_identity" class="alias">`_.eachRight` -> `forEachRight－－－－－`</a>
* <a href="#_everycollection-predicate_identity">`_.every－－－－－`</a>
* <a href="#_filtercollection-predicate_identity">`_.filter－－－－－`</a>
* <a href="#_findcollection-predicate_identity-fromindex0">`_.find－－－－－`</a>
* <a href="#_findlastcollection-predicate_identity-fromindexcollectionlength-1">`_.findLast－－－－－`</a>
* <a href="#_flatmapcollection-iteratee_identity">`_.flatMap－－－－－`</a>
* <a href="#_flatmapdeepcollection-iteratee_identity">`_.flatMapDeep－－－－－`</a>
* <a href="#_flatmapdepthcollection-iteratee_identity-depth1">`_.flatMapDepth－－－－－`</a>
* <a href="#_foreachcollection-iteratee_identity">`_.forEach－－－－－`</a>
* <a href="#_foreachrightcollection-iteratee_identity">`_.forEachRight－－－－－`</a>
* <a href="#_groupbycollection-iteratee_identity">`_.groupBy－－－－－`</a>
* <a href="#_includescollection-value-fromindex0">`_.includes－－－－－`</a>
* <a href="#_invokemapcollection-path-args">`_.invokeMap－－－－－`</a>
* <a href="#_keybycollection-iteratee_identity">`_.keyBy－－－－－`</a>
* <a href="#_mapcollection-iteratee_identity">`_.map－－－－－`</a>
* <a href="#_orderbycollection-iteratees_identity-orders">`_.orderBy－－－－－`</a>
* <a href="#_partitioncollection-predicate_identity">`_.partition－－－－－`</a>
* <a href="#_reducecollection-iteratee_identity-accumulator">`_.reduce－－－－－`</a>
* <a href="#_reducerightcollection-iteratee_identity-accumulator">`_.reduceRight－－－－－`</a>
* <a href="#_rejectcollection-predicate_identity">`_.reject－－－－－`</a>
* <a href="#_samplecollection">`_.sample－－－－－`</a>
* <a href="#_samplesizecollection-n1">`_.sampleSize－－－－－`</a>
* <a href="#_shufflecollection">`_.shuffle－－－－－`</a>
* <a href="#_sizecollection">`_.size－－－－－`</a>
* <a href="#_somecollection-predicate_identity">`_.some－－－－－`</a>
* <a href="#_sortbycollection-iteratees_identity">`_.sortBy－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Date`
* <a href="#_now">`_.now－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Function`
* <a href="#_aftern-func">`_.after－－－－－`</a>
* <a href="#_aryfunc-nfunclength">`_.ary－－－－－`</a>
* <a href="#_beforen-func">`_.before－－－－－`</a>
* <a href="#_bindfunc-thisarg-partials">`_.bind－－－－－`</a>
* <a href="#_bindkeyobject-key-partials">`_.bindKey－－－－－`</a>
* <a href="#_curryfunc-arityfunclength">`_.curry－－－－－`</a>
* <a href="#_curryrightfunc-arityfunclength">`_.curryRight－－－－－`</a>
* <a href="#_debouncefunc-wait0-options">`_.debounce－－－－－`</a>
* <a href="#_deferfunc-args">`_.defer－－－－－`</a>
* <a href="#_delayfunc-wait-args">`_.delay－－－－－`</a>
* <a href="#_flipfunc">`_.flip－－－－－`</a>
* <a href="#_memoizefunc-resolver">`_.memoize－－－－－`</a>
* <a href="#_negatepredicate">`_.negate－－－－－`</a>
* <a href="#_oncefunc">`_.once－－－－－`</a>
* <a href="#_overargsfunc-transforms_identity">`_.overArgs－－－－－`</a>
* <a href="#_partialfunc-partials">`_.partial－－－－－`</a>
* <a href="#_partialrightfunc-partials">`_.partialRight－－－－－`</a>
* <a href="#_reargfunc-indexes">`_.rearg－－－－－`</a>
* <a href="#_restfunc-startfunclength-1">`_.rest－－－－－`</a>
* <a href="#_spreadfunc-start0">`_.spread－－－－－`</a>
* <a href="#_throttlefunc-wait0-options">`_.throttle－－－－－`</a>
* <a href="#_unaryfunc">`_.unary－－－－－`</a>
* <a href="#_wrapvalue-wrapperidentity">`_.wrap－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Lang`
* <a href="#_castarrayvalue">`_.castArray－－－－－`</a>
* <a href="#_clonevalue">`_.clone－－－－－`</a>
* <a href="#_clonedeepvalue">`_.cloneDeep－－－－－`</a>
* <a href="#_clonedeepwithvalue-customizer">`_.cloneDeepWith－－－－－`</a>
* <a href="#_clonewithvalue-customizer">`_.cloneWith－－－－－`</a>
* <a href="#_conformstoobject-source">`_.conformsTo－－－－－`</a>
* <a href="#_eqvalue-other">`_.eq－－－－－`</a>
* <a href="#_gtvalue-other">`_.gt－－－－－`</a>
* <a href="#_gtevalue-other">`_.gte－－－－－`</a>
* <a href="#_isargumentsvalue">`_.isArguments－－－－－`</a>
* <a href="#_isarrayvalue">`_.isArray－－－－－`</a>
* <a href="#_isarraybuffervalue">`_.isArrayBuffer－－－－－`</a>
* <a href="#_isarraylikevalue">`_.isArrayLike－－－－－`</a>
* <a href="#_isarraylikeobjectvalue">`_.isArrayLikeObject－－－－－`</a>
* <a href="#_isbooleanvalue">`_.isBoolean－－－－－`</a>
* <a href="#_isbuffervalue">`_.isBuffer－－－－－`</a>
* <a href="#_isdatevalue">`_.isDate－－－－－`</a>
* <a href="#_iselementvalue">`_.isElement－－－－－`</a>
* <a href="#_isemptyvalue">`_.isEmpty－－－－－`</a>
* <a href="#_isequalvalue-other">`_.isEqual－－－－－`</a>
* <a href="#_isequalwithvalue-other-customizer">`_.isEqualWith－－－－－`</a>
* <a href="#_iserrorvalue">`_.isError－－－－－`</a>
* <a href="#_isfinitevalue">`_.isFinite－－－－－`</a>
* <a href="#_isfunctionvalue">`_.isFunction－－－－－`</a>
* <a href="#_isintegervalue">`_.isInteger－－－－－`</a>
* <a href="#_islengthvalue">`_.isLength－－－－－`</a>
* <a href="#_ismapvalue">`_.isMap－－－－－`</a>
* <a href="#_ismatchobject-source">`_.isMatch－－－－－`</a>
* <a href="#_ismatchwithobject-source-customizer">`_.isMatchWith－－－－－`</a>
* <a href="#_isnanvalue">`_.isNaN－－－－－`</a>
* <a href="#_isnativevalue">`_.isNative－－－－－`</a>
* <a href="#_isnilvalue">`_.isNil－－－－－`</a>
* <a href="#_isnullvalue">`_.isNull－－－－－`</a>
* <a href="#_isnumbervalue">`_.isNumber－－－－－`</a>
* <a href="#_isobjectvalue">`_.isObject－－－－－`</a>
* <a href="#_isobjectlikevalue">`_.isObjectLike－－－－－`</a>
* <a href="#_isplainobjectvalue">`_.isPlainObject－－－－－`</a>
* <a href="#_isregexpvalue">`_.isRegExp－－－－－`</a>
* <a href="#_issafeintegervalue">`_.isSafeInteger－－－－－`</a>
* <a href="#_issetvalue">`_.isSet－－－－－`</a>
* <a href="#_isstringvalue">`_.isString－－－－－`</a>
* <a href="#_issymbolvalue">`_.isSymbol－－－－－`</a>
* <a href="#_istypedarrayvalue">`_.isTypedArray－－－－－`</a>
* <a href="#_isundefinedvalue">`_.isUndefined－－－－－`</a>
* <a href="#_isweakmapvalue">`_.isWeakMap－－－－－`</a>
* <a href="#_isweaksetvalue">`_.isWeakSet－－－－－`</a>
* <a href="#_ltvalue-other">`_.lt－－－－－`</a>
* <a href="#_ltevalue-other">`_.lte－－－－－`</a>
* <a href="#_toarrayvalue">`_.toArray－－－－－`</a>
* <a href="#_tofinitevalue">`_.toFinite－－－－－`</a>
* <a href="#_tointegervalue">`_.toInteger－－－－－`</a>
* <a href="#_tolengthvalue">`_.toLength－－－－－`</a>
* <a href="#_tonumbervalue">`_.toNumber－－－－－`</a>
* <a href="#_toplainobjectvalue">`_.toPlainObject－－－－－`</a>
* <a href="#_tosafeintegervalue">`_.toSafeInteger－－－－－`</a>
* <a href="#_tostringvalue">`_.toString－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Math`
* <a href="#_addaugend-addend">`_.add－－－－－`</a>
* <a href="#_ceilnumber-precision0">`_.ceil－－－－－`</a>
* <a href="#_dividedividend-divisor">`_.divide－－－－－`</a>
* <a href="#_floornumber-precision0">`_.floor－－－－－`</a>
* <a href="#_maxarray">`_.max－－－－－`</a>
* <a href="#_maxbyarray-iteratee_identity">`_.maxBy－－－－－`</a>
* <a href="#_meanarray">`_.mean－－－－－`</a>
* <a href="#_meanbyarray-iteratee_identity">`_.meanBy－－－－－`</a>
* <a href="#_minarray">`_.min－－－－－`</a>
* <a href="#_minbyarray-iteratee_identity">`_.minBy－－－－－`</a>
* <a href="#_multiplymultiplier-multiplicand">`_.multiply－－－－－`</a>
* <a href="#_roundnumber-precision0">`_.round－－－－－`</a>
* <a href="#_subtractminuend-subtrahend">`_.subtract－－－－－`</a>
* <a href="#_sumarray">`_.sum－－－－－`</a>
* <a href="#_sumbyarray-iteratee_identity">`_.sumBy－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Number`
* <a href="#_clampnumber-lower-upper">`_.clamp－－－－－`</a>
* <a href="#_inrangenumber-start0-end">`_.inRange－－－－－`</a>
* <a href="#_randomlower0-upper1-floating">`_.random－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Object`
* <a href="#_assignobject-sources">`_.assign－－－－－`</a>
* <a href="#_assigninobject-sources">`_.assignIn－－－－－`</a>
* <a href="#_assigninwithobject-sources-customizer">`_.assignInWith－－－－－`</a>
* <a href="#_assignwithobject-sources-customizer">`_.assignWith－－－－－`</a>
* <a href="#_atobject-paths">`_.at－－－－－`</a>
* <a href="#_createprototype-properties">`_.create－－－－－`</a>
* <a href="#_defaultsobject-sources">`_.defaults－－－－－`</a>
* <a href="#_defaultsdeepobject-sources">`_.defaultsDeep－－－－－`</a>
* <a href="#_topairsobject" class="alias">`_.entries` -> `toPairs－－－－－`</a>
* <a href="#_topairsinobject" class="alias">`_.entriesIn` -> `toPairsIn－－－－－`</a>
* <a href="#_assigninobject-sources" class="alias">`_.extend` -> `assignIn－－－－－`</a>
* <a href="#_assigninwithobject-sources-customizer" class="alias">`_.extendWith` -> `assignInWith－－－－－`</a>
* <a href="#_findkeyobject-predicate_identity">`_.findKey－－－－－`</a>
* <a href="#_findlastkeyobject-predicate_identity">`_.findLastKey－－－－－`</a>
* <a href="#_forinobject-iteratee_identity">`_.forIn－－－－－`</a>
* <a href="#_forinrightobject-iteratee_identity">`_.forInRight－－－－－`</a>
* <a href="#_forownobject-iteratee_identity">`_.forOwn－－－－－`</a>
* <a href="#_forownrightobject-iteratee_identity">`_.forOwnRight－－－－－`</a>
* <a href="#_functionsobject">`_.functions－－－－－`</a>
* <a href="#_functionsinobject">`_.functionsIn－－－－－`</a>
* <a href="#_getobject-path-defaultvalue">`_.get－－－－－`</a>
* <a href="#_hasobject-path">`_.has－－－－－`</a>
* <a href="#_hasinobject-path">`_.hasIn－－－－－`</a>
* <a href="#_invertobject">`_.invert－－－－－`</a>
* <a href="#_invertbyobject-iteratee_identity">`_.invertBy－－－－－`</a>
* <a href="#_invokeobject-path-args">`_.invoke－－－－－`</a>
* <a href="#_keysobject">`_.keys－－－－－`</a>
* <a href="#_keysinobject">`_.keysIn－－－－－`</a>
* <a href="#_mapkeysobject-iteratee_identity">`_.mapKeys－－－－－`</a>
* <a href="#_mapvaluesobject-iteratee_identity">`_.mapValues－－－－－`</a>
* <a href="#_mergeobject-sources">`_.merge－－－－－`</a>
* <a href="#_mergewithobject-sources-customizer">`_.mergeWith－－－－－`</a>
* <a href="#_omitobject-props">`_.omit－－－－－`</a>
* <a href="#_omitbyobject-predicate_identity">`_.omitBy－－－－－`</a>
* <a href="#_pickobject-props">`_.pick－－－－－`</a>
* <a href="#_pickbyobject-predicate_identity">`_.pickBy－－－－－`</a>
* <a href="#_resultobject-path-defaultvalue">`_.result－－－－－`</a>
* <a href="#_setobject-path-value">`_.set－－－－－`</a>
* <a href="#_setwithobject-path-value-customizer">`_.setWith－－－－－`</a>
* <a href="#_topairsobject">`_.toPairs－－－－－`</a>
* <a href="#_topairsinobject">`_.toPairsIn－－－－－`</a>
* <a href="#_transformobject-iteratee_identity-accumulator">`_.transform－－－－－`</a>
* <a href="#_unsetobject-path">`_.unset－－－－－`</a>
* <a href="#_updateobject-path-updater">`_.update－－－－－`</a>
* <a href="#_updatewithobject-path-updater-customizer">`_.updateWith－－－－－`</a>
* <a href="#_valuesobject">`_.values－－－－－`</a>
* <a href="#_valuesinobject">`_.valuesIn－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Seq`
* <a href="#_value">`_－－－－－`</a>
* <a href="#_chainvalue">`_.chain－－－－－`</a>
* <a href="#_tapvalue-interceptor">`_.tap－－－－－`</a>
* <a href="#_thruvalue-interceptor">`_.thru－－－－－`</a>
* <a href="#_prototypesymboliterator">`_.prototype[Symbol.iterator]－－－－－`</a>
* <a href="#_prototypeatpaths">`_.prototype.at－－－－－`</a>
* <a href="#_prototypechain">`_.prototype.chain－－－－－`</a>
* <a href="#_prototypecommit">`_.prototype.commit－－－－－`</a>
* <a href="#_prototypenext">`_.prototype.next－－－－－`</a>
* <a href="#_prototypeplantvalue">`_.prototype.plant－－－－－`</a>
* <a href="#_prototypereverse">`_.prototype.reverse－－－－－`</a>
* <a href="#_prototypevalue" class="alias">`_.prototype.toJSON` -> `value－－－－－`</a>
* <a href="#_prototypevalue">`_.prototype.value－－－－－`</a>
* <a href="#_prototypevalue" class="alias">`_.prototype.valueOf` -> `value－－－－－`</a>

<!-- /div -->

<!-- div -->

## `String`
* <a href="#_camelcasestring">`_.camelCase－－－－－`</a>
* <a href="#_capitalizestring">`_.capitalize－－－－－`</a>
* <a href="#_deburrstring">`_.deburr－－－－－`</a>
* <a href="#_endswithstring-target-positionstringlength">`_.endsWith－－－－－`</a>
* <a href="#_escapestring">`_.escape－－－－－`</a>
* <a href="#_escaperegexpstring">`_.escapeRegExp－－－－－`</a>
* <a href="#_kebabcasestring">`_.kebabCase－－－－－`</a>
* <a href="#_lowercasestring">`_.lowerCase－－－－－`</a>
* <a href="#_lowerfirststring">`_.lowerFirst－－－－－`</a>
* <a href="#_padstring-length0-chars">`_.pad－－－－－`</a>
* <a href="#_padendstring-length0-chars">`_.padEnd－－－－－`</a>
* <a href="#_padstartstring-length0-chars">`_.padStart－－－－－`</a>
* <a href="#_parseintstring-radix10">`_.parseInt－－－－－`</a>
* <a href="#_repeatstring-n1">`_.repeat－－－－－`</a>
* <a href="#_replacestring-pattern-replacement">`_.replace－－－－－`</a>
* <a href="#_snakecasestring">`_.snakeCase－－－－－`</a>
* <a href="#_splitstring-separator-limit">`_.split－－－－－`</a>
* <a href="#_startcasestring">`_.startCase－－－－－`</a>
* <a href="#_startswithstring-target-position0">`_.startsWith－－－－－`</a>
* <a href="#_templatestring-options">`_.template－－－－－`</a>
* <a href="#_tolowerstring">`_.toLower－－－－－`</a>
* <a href="#_toupperstring">`_.toUpper－－－－－`</a>
* <a href="#_trimstring-charswhitespace">`_.trim－－－－－`</a>
* <a href="#_trimendstring-charswhitespace">`_.trimEnd－－－－－`</a>
* <a href="#_trimstartstring-charswhitespace">`_.trimStart－－－－－`</a>
* <a href="#_truncatestring-options">`_.truncate－－－－－`</a>
* <a href="#_unescapestring">`_.unescape－－－－－`</a>
* <a href="#_uppercasestring">`_.upperCase－－－－－`</a>
* <a href="#_upperfirststring">`_.upperFirst－－－－－`</a>
* <a href="#_wordsstring-pattern">`_.words－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Util`
* <a href="#_attemptfunc-args">`_.attempt－－－－－`</a>
* <a href="#_bindallobject-methodnames">`_.bindAll－－－－－`</a>
* <a href="#_condpairs">`_.cond－－－－－`</a>
* <a href="#_conformssource">`_.conforms－－－－－`</a>
* <a href="#_constantvalue">`_.constant－－－－－`</a>
* <a href="#_defaulttovalue-defaultvalue">`_.defaultTo－－－－－`</a>
* <a href="#_flowfuncs">`_.flow－－－－－`</a>
* <a href="#_flowrightfuncs">`_.flowRight－－－－－`</a>
* <a href="#_identityvalue">`_.identity－－－－－`</a>
* <a href="#_iterateefunc_identity">`_.iteratee－－－－－`</a>
* <a href="#_matchessource">`_.matches－－－－－`</a>
* <a href="#_matchespropertypath-srcvalue">`_.matchesProperty－－－－－`</a>
* <a href="#_methodpath-args">`_.method－－－－－`</a>
* <a href="#_methodofobject-args">`_.methodOf－－－－－`</a>
* <a href="#_mixinobjectlodash-source-options">`_.mixin－－－－－`</a>
* <a href="#_noconflict">`_.noConflict－－－－－`</a>
* <a href="#_noop">`_.noop－－－－－`</a>
* <a href="#_nthargn0">`_.nthArg－－－－－`</a>
* <a href="#_overiteratees_identity">`_.over－－－－－`</a>
* <a href="#_overeverypredicates_identity">`_.overEvery－－－－－`</a>
* <a href="#_oversomepredicates_identity">`_.overSome－－－－－`</a>
* <a href="#_propertypath">`_.property－－－－－`</a>
* <a href="#_propertyofobject">`_.propertyOf－－－－－`</a>
* <a href="#_rangestart0-end-step1">`_.range－－－－－`</a>
* <a href="#_rangerightstart0-end-step1">`_.rangeRight－－－－－`</a>
* <a href="#_runincontextcontextroot">`_.runInContext－－－－－`</a>
* <a href="#_stubarray">`_.stubArray－－－－－`</a>
* <a href="#_stubfalse">`_.stubFalse－－－－－`</a>
* <a href="#_stubobject">`_.stubObject－－－－－`</a>
* <a href="#_stubstring">`_.stubString－－－－－`</a>
* <a href="#_stubtrue">`_.stubTrue－－－－－`</a>
* <a href="#_timesn-iteratee_identity">`_.times－－－－－`</a>
* <a href="#_topathvalue">`_.toPath－－－－－`</a>
* <a href="#_uniqueidprefix">`_.uniqueId－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Properties`
* <a href="#_version">`_.VERSION－－－－－`</a>
* <a href="#_templatesettings">`_.templateSettings－－－－－`</a>
* <a href="#_templatesettingsescape">`_.templateSettings.escape－－－－－`</a>
* <a href="#_templatesettingsevaluate">`_.templateSettings.evaluate－－－－－`</a>
* <a href="#_templatesettingsimports">`_.templateSettings.imports－－－－－`</a>
* <a href="#_templatesettingsinterpolate">`_.templateSettings.interpolate－－－－－`</a>
* <a href="#_templatesettingsvariable">`_.templateSettings.variable－－－－－`</a>

<!-- /div -->

<!-- div -->

## `Methods`
* <a href="#_templatesettingsimports_">`_.templateSettings.imports._－－－－－`</a>

<!-- /div -->

<!-- /div -->

<!-- div class="doc-container" -->

<!-- div -->

## `“Array” Methods`

<!-- div -->

<h3 id="_chunkarray-size1"><code>_.chunk(array, [size=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6670 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.chunk "查看Npm包") [&#x24C9;][1]

按照指定长度切割一个数组放在新的数组中．如果数组不能均等的切分，则最后的块包含剩余部分．

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: 要处理的数组.
2. `[size=1]` *(number)*: 每个块的长度

#### 返回结果
*(Array)*: 返回新的数组

####示例
```js
_.chunk(['a', 'b', 'c', 'd'], 2);
// => [['a', 'b'], ['c', 'd']]

_.chunk(['a', 'b', 'c', 'd'], 3);
// => [['a', 'b', 'c'], ['d']]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_compactarray"><code>_.compact(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6705 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.compact "查看Npm包") [&#x24C9;][1]

创建一个数组移除所有非法字符，包括　false, null, 0, "", undefined, NaN

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: 要处理的数组.

#### 返回结果
*(Array)*: 返回过滤后的新数组．

####示例
```js
_.compact([0, 1, false, 2, '', 3]);
// => [1, 2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_concatarray-values"><code>_.concat(array, [values])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6742 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.concat "查看Npm包") [&#x24C9;][1]

将一个数组与其他数组／值链接起来，放在一个新的数组中．

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: 链接的数组
2. `[values]` *(...&#42;)*:  链接的值

#### 返回结果
*(Array)*: 返回新链接后的新数组

####示例
```js
var array = [1];
var other = _.concat(array, 2, [3], [[4]]);

console.log(other);
// => [1, 2, 3, [4]]

console.log(array);
// => [1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_differencearray-values"><code>_.difference(array, [values])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6778 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.difference "查看Npm包") [&#x24C9;][1]

用 [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)
的方式去判断，将数组中不包含在提供的数组中的元素提取出来，放在新的数组中．
<br>
<br>
**提示:** 不同于 `_.pullAll`, 这个方法返回新的数组．

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: The array to inspect.
2. `[values]` *(...Array)*: The values to exclude.

#### 返回结果
*(Array)*: Returns the new array of filtered values.

####示例
```js
_.difference([2, 1], [2, 3]);
// => [1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_differencebyarray-values-iteratee_identity"><code>_.differenceBy(array, [values], [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6810 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.differenceby "查看Npm包") [&#x24C9;][1]

这个方法类似于 `_.difference` 的排除，他用`iteratee` 作为`array` 和 `values` 的比较标准
结果值是从第一数组中选出，这种方法比较时调用一个参数:<br>
*(value)*.
<br>
<br>
**提示:** 不同于 `_.pullAllBy`, 这个方法返回新的数组．

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: 取值数组.
2. `[values]` *(...Array)*: 比对数组.
3. `[iteratee=_.identity]` *(Function)*: 每个元素比对调用的方法

#### 返回结果
*(Array)*: 返回新的数组

####示例
```js
console.log(_.differenceBy([2.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7], [1.9,2.0,2.3, 3.4], Math.floor));
// => [1.2, 1.3, 1.4, 1.5]

console.log(Math.floor(0.1));
//0
//Math.floor求一个最接近它的整数，它的值小于或等于这个浮点数。
// The `_.property` iteratee shorthand.
_.differenceBy([{ 'x': 2 }, { 'x': 1 }], [{ 'x': 1 }], 'x');
// => [{ 'x': 2 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_differencewitharray-values-comparator"><code>_.differenceWith(array, [values], [comparator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6843 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.differencewith "查看Npm包") [&#x24C9;][1]

这个方法类似于 `_.difference` 的去除， 它接受`array`中的元素比较`. 结果值是从第一数组中选出. 这种比较使用两个参数: *(arrVal, othVal)*.
<br>
<br>
**提示:** 不同于 `_.pullAllWith`, 这个方法返回新的数组．

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: 要检查的数组
2. `[values]` *(...Array)*: 排除这些值
3. `[comparator]` *(Function)*: 每个元素比较调用。

#### 返回结果
*(Array)*:返回过滤后的新数组

####示例
```js
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];

_.differenceWith(objects, [{ 'x': 1, 'y': 2 }], _.isEqual);
// => [{ 'x': 2, 'y': 1 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_droparray-n1"><code>_.drop(array, [n=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6878 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.drop "查看Npm包") [&#x24C9;][1]

从开始位置剔除掉指定位置的元素，剩余部分放在新的数组．默认剔除第一位．

#### 起始版本
0.5.0
#### 参数
1. `array` *(Array)*: 处理的数组.
2. `[n=1]` *(number)*: 结束位置.

#### 返回结果
*(Array)*: 返回去除之后的数组.

####示例
```js
_.drop([1, 2, 3]);
// => [2, 3]

_.drop([1, 2, 3], 2);
// => [3]

_.drop([1, 2, 3], 5);
// => []

_.drop([1, 2, 3], 0);
// => [1, 2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_droprightarray-n1"><code>_.dropRight(array, [n=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6912 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.dropright "查看Npm包") [&#x24C9;][1]

从最后位置倒序剔除掉指定位置的元素，剩余部分放在新的数组．默认剔除第一位．

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: 处理的数组.
2. `[n=1]` *(number)*: 结束位置.

#### 返回结果
*(Array)*: 剩余数组.

####示例
```js
_.dropRight([1, 2, 3]);
// => [1, 2]

_.dropRight([1, 2, 3], 2);
// => [1]

_.dropRight([1, 2, 3], 5);
// => []

_.dropRight([1, 2, 3], 0);
// => [1, 2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_droprightwhilearray-predicate_identity"><code>_.dropRightWhile(array, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6957 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.droprightwhile "查看Npm包") [&#x24C9;][1]

按照指定的方法剔除元素，需要三个参数: *(value, index, array)*.

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: 处理的数组.
2. `[predicate=_.identity]` *(Function)*: 剔除规则.

#### 返回结果
*(Array)*:返回新的数组.

####示例
```js
var users = [
  { 'user': 'barney',  'active': true },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': false }
];

_.dropRightWhile(users, function(o) { return !o.active; });
// => objects for ['barney']

// The `_.matches` 的缩写
_.dropRightWhile(users, { 'user': 'pebbles', 'active': false });
// => objects for ['barney', 'fred']

// The `_.matchesProperty` 的缩写
_.dropRightWhile(users, ['active', false]);
// => objects for ['barney']

// The `_.property` 的缩写
_.dropRightWhile(users, 'active');
// => objects for ['barney', 'fred', 'pebbles']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_dropwhilearray-predicate_identity"><code>_.dropWhile(array, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L6999 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.dropwhile "查看Npm包") [&#x24C9;][1]

与dropWhile极其相似

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: 处理的数组.
2. `[predicate=_.identity]` *(Function)*: 剔除标准.

#### 返回结果
*(Array)*: 返回的数组

####示例
```js
var users = [
  { 'user': 'barney',  'active': false },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': true }
];

_.dropWhile(users, function(o) { return !o.active; });
// => objects for ['pebbles']

// The `_.matches` 的缩写
_.dropWhile(users, { 'user': 'barney', 'active': false });
// => objects for ['fred', 'pebbles']

// The `_.matchesProperty` 的缩写
_.dropWhile(users, ['active', false]);
// => objects for ['pebbles']

// The `_.property` 的缩写
_.dropWhile(users, 'active');
// => objects for ['barney', 'fred', 'pebbles']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_fillarray-value-start0-endarraylength"><code>_.fill(array, value, [start=0], [end=array.length])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7034 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.fill "查看Npm包") [&#x24C9;][1]

用指定字符从开始位置替换到结束位置，但不包括结束位置.

<br>
<br>
**提示:** 这个方法会使得数组发生变化.

#### 起始版本
3.2.0
#### 参数
1. `array` *(Array)*: 要替换的数组.
2. `value` *(&#42;)*: 替换的值.
3. `[start=0]` *(number)*: 开始位置.
4. `[end=array.length]` *(number)*: 结束位置，不会替换改位置的元素.

#### 返回结果
*(Array)*: 返回数组.

####示例
```js
var array = [1, 2, 3];

_.fill(array, 'a');
console.log(array);
// => ['a', 'a', 'a']

_.fill(Array(3), 2);
// => [2, 2, 2]

_.fill([4, 6, 8, 10], '*', 1, 3);
// => [4, '*', '*', 10]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_findindexarray-predicate_identity-fromindex0"><code>_.findIndex(array, [predicate=_.identity], [fromIndex=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7082 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.findindex "查看Npm包") [&#x24C9;][1]

这个方法类似`_.find` 返回的是找到的该元素的位置，而不是元素本身．

#### 起始版本
1.1.0
#### 参数
1. `array` *(Array)*: 查找的数组.
2. `[predicate=_.identity]` *(Function)*: 查找的条件.
3. `[fromIndex=0]` *(number)*: 查找的起始位置.

#### 返回结果
*(number)*: 找到返回位置，否则返回-1．

####示例
```js
var users = [
  { 'user': 'barney',  'active': false },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': true }
];

_.findIndex(users, function(o) { return o.user == 'barney'; });
// => 0

// The `_.matches` 的缩写
_.findIndex(users, { 'user': 'fred', 'active': false });
// => 1

// The `_.matchesProperty` 的缩写
_.findIndex(users, ['active', false]);
// => 0

// The `_.property` 的缩写
_.findIndex(users, 'active');
// => 2
```
---

<!-- /div -->

<!-- div -->

<h3 id="_findlastindexarray-predicate_identity-fromindexarraylength-1"><code>_.findLastIndex(array, [predicate=_.identity], [fromIndex=array.length-1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7130 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.findlastindex "查看Npm包") [&#x24C9;][1]

这个方法类似于 `_.findIndex`按照倒序的方式查找一个元素的位置．
其实就是查找最后一个元素的位置．

#### 起始版本
2.0.0
#### 参数
1. `array` *(Array)*:查找的元素
2. `[predicate=_.identity]` *(Function)*:查找的条件
3. `[fromIndex=array.length-1]` *(number)*: 查找的起始位置

#### 返回结果
*(number)*:找到返回位置，没找到返回-1.

####示例
```js
var users = [
  { 'user': 'barney',  'active': true },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': false }
];

_.findLastIndex(users, function(o) { return o.user == 'pebbles'; });
// => 2

// The `_.matches` 的缩写
_.findLastIndex(users, { 'user': 'barney', 'active': true });
// => 0

// The `_.matchesProperty` 的缩写
_.findLastIndex(users, ['active', false]);
// => 2

// The `_.property` 的缩写
_.findLastIndex(users, 'active');
// => 0
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flattenarray"><code>_.flatten(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7159 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flatten "查看Npm包") [&#x24C9;][1]

给一个多级数组降级，弄平．

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: 要弄平的数组

#### 返回结果
*(Array)*:弄平后的数组

####示例
```js
_.flatten([1, [2, [3, [4]], 5]]);
// => [1, 2, [3, [4]], 5]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flattendeeparray"><code>_.flattenDeep(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7178 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flattendeep "查看Npm包") [&#x24C9;][1]

推平数组

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: 要推平的数组

#### 返回结果
*(Array)*: 推平后的数组

####示例
```js
_.flattenDeep([1, [2, [3, [4]], 5]]);
// => [1, 2, 3, 4, 5]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flattendeptharray-depth1"><code>_.flattenDepth(array, [depth=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7203 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flattendepth "查看Npm包") [&#x24C9;][1]

按照指定深度扁平化数组

#### 起始版本
4.4.0
#### 参数
1. `array` *(Array)*: 需要扁平的数组.
2. `[depth=1]` *(number)*: 最大递归的深度

#### 返回结果
*(Array)*: 返回扁平后的数组.

####示例
```js
var array = [1, [2, [3, [4]], 5]];

_.flattenDepth(array, 1);
// => [1, 2, [3, [4]], 5]

_.flattenDepth(array, 2);
// => [1, 2, 3, [4], 5]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_frompairspairs"><code>_.fromPairs(pairs)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7227 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.frompairs "查看Npm包") [&#x24C9;][1]

通过键值对，返回键值对对象．

#### 起始版本
4.0.0
#### 参数
1. `pairs` *(Array)*: 键值对

#### 返回结果
*(Object)*: 返回新的对象.

####示例
```js
_.fromPairs([['a', 1], ['b', 2]]);
// => { 'a': 1, 'b': 2 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_headarray"><code>_.head(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7257 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.head "查看Npm包") [&#x24C9;][1]

返回数组的第一个元素

#### 起始版本
0.1.0
#### Aliases
*_.first*

#### 参数
1. `array` *(Array)*: 数组

#### 返回结果
*(&#42;)*: 返回第一个元素组成的数组

####示例
```js
_.head([1, 2, 3]);
// => 1

_.head([]);
// => undefined
```
---

<!-- /div -->

<!-- div -->

<h3 id="_indexofarray-value-fromindex0"><code>_.indexOf(array, value, [fromIndex=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7284 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.indexof "查看Npm包") [&#x24C9;][1]

找到value出现的指定位置，判断依据于[`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: 查找的数组
2. `value` *(&#42;)*: 搜寻的值.
3. `[fromIndex=0]` *(number)*: 搜索的起始位置.

#### 返回结果
*(number)*: 返回下标, 没找到返回 `-1`.

####示例
```js
_.indexOf([1, 2, 1, 2], 2);
// => 1

// Search from the `fromIndex`.
_.indexOf([1, 2, 1, 2], 2, 2);
// => 3
```
---

<!-- /div -->

<!-- div -->

<h3 id="_initialarray"><code>_.initial(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7310 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.initial "查看Npm包") [&#x24C9;][1]

获取数组中除过最后一个元素的其他元素

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: 处理的数组.

#### 返回结果
*(Array)*: 返回切割后的数组.

####示例
```js
_.initial([1, 2, 3]);
// => [1, 2]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_intersectionarrays"><code>_.intersection([arrays])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7332 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.intersection "查看Npm包") [&#x24C9;][1]

找出两个数组中的相同元素，存在新的数组中．新数组的元素和其顺序依据于第一个数组．
判断依据 [`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)

#### 起始版本
0.1.0
#### 参数
1. `[arrays]` *(...Array)*: 处理的数组

#### 返回结果
*(Array)*: 返回新的数组

####示例
```js
_.intersection([2, 1], [2, 3]);
// => [2]
_.intersection([2, 1], [2, 1,2]);
// => [2, 1]
_.intersection([2,5,3,1], [1,2, 3,6]);
// => [2, 3, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_intersectionbyarrays-iteratee_identity"><code>_.intersectionBy([arrays], [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7362 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.intersectionby "查看Npm包") [&#x24C9;][1]

找出两个数组中的相同元素，存在新的数组中．新数组的元素和其顺序依据于第一个数组．
自定义判断依据

#### 起始版本
4.0.0
#### 参数
1. `[arrays]` *(...Array)*:处理的数组
2. `[iteratee=_.identity]` *(Function)*: 每个元素比较时调用的方法

#### 返回结果
*(Array)*: 返回新的数组

####示例
```js
_.intersectionBy([2.1, 1.2], [2.3, 3.4], Math.floor);
// => [2.1]

// The `_.property` 的缩写
_.intersectionBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 1 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_intersectionwitharrays-comparator"><code>_.intersectionWith([arrays], [comparator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7397 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.intersectionwith "查看Npm包") [&#x24C9;][1]

找出两个数组中的相同元素，存在新的数组中．新数组的元素和其顺序依据于第一个数组．
自定义判断依据
这个方法需要两个参数: *(arrVal, othVal)*.

#### 起始版本
4.0.0
#### 参数
1. `[arrays]` *(...Array)*: 待处理的数组
2. `[comparator]` *(Function)*: 每个元素判断的依据

#### 返回结果
*(Array)*: 返回新数组

####示例
```js
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.intersectionWith(objects, others, _.isEqual);
// => [{ 'x': 1, 'y': 2 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_joinarray-separator-"><code>_.join(array, [separator=','])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7426 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.join "查看Npm包") [&#x24C9;][1]

用指定字符串串联数组里面的元素，返回字符串

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*:需要串联的数组
2. `[separator=',']` *(string)*: 串联的字符

#### 返回结果
*(string)*: 返回合并的数组

####示例
```js
console.log(_.join(['a', 'b', 'c'], '~'));
// => 'a~b~c'
console.log(_.join(['a', 'b', 'c'], ','));
// => "a,b,c"
```
---

<!-- /div -->

<!-- div -->

<h3 id="_lastarray"><code>_.last(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7444 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.last "查看Npm包") [&#x24C9;][1]

返回数组的最后一个元素

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: 处理的数组.

#### 返回结果
*(&#42;)*: 返回最后一个元素组成的数组

####示例
```js
_.last([1, 2, 3]);
// => 3
```
---

<!-- /div -->

<!-- div -->

<h3 id="_lastindexofarray-value-fromindexarraylength-1"><code>_.lastIndexOf(array, value, [fromIndex=array.length-1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7470 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.lastindexof "查看Npm包") [&#x24C9;][1]

返回想要找的元素的最后一次出现的位置

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: 查找的数组
2. `value` *(&#42;)*: 寻找的值.
3. `[fromIndex=array.length-1]` *(number)*: 起始位置

#### 返回结果
*(number)*: 返回位置，没找到返回-1

####示例
```js
_.lastIndexOf([1, 2, 1, 2], 2);
// => 3

// Search from the `fromIndex`.
_.lastIndexOf([1, 2, 1, 2], 2, 2);
// => 1
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ntharray-n0"><code>_.nth(array, [n=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7506 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.nth "查看Npm包") [&#x24C9;][1]

返回指定位置的元素．如果元素是负数则按照倒序取值．

#### 起始版本
4.11.0
#### 参数
1. `array` *(Array)*:　处理的数组
2. `[n=0]` *(number)*: 取值的位置

#### 返回结果
*(&#42;)*: 指定位置元素的数组

####示例
```js
var array = ['a', 'b', 'c', 'd'];

_.nth(array, 1);
// => 'b'

_.nth(array, -2);
// => 'c';
```
---

<!-- /div -->

<!-- div -->

<h3 id="_pullarray-values"><code>_.pull(array, [values])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7533 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pull "查看Npm包") [&#x24C9;][1]

移除数组中指定的所有元素，判断依据
[`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)
<br>
<br>
**提示:** 不同于 `_.without`,这个方法使数组发生变化..使用 `_.remove`去删除数据的．

#### 起始版本
2.0.0
#### 参数
1. `array` *(Array)*:修改的数组
2. `[values]` *(...&#42;)*: 移除的值

#### 返回结果
*(Array)*:返回数组

####示例
```js
var array = ['a', 'b', 'c', 'a', 'b', 'c',1,3,45,677,6];
 
_.pull(array, 'a', 'c',1);
console.log(array);
// 0: "b"
// 1: "b"
// 2: 3
// 3: 45
// 4: 677
// 5: 6
```
---

<!-- /div -->

<!-- div -->

<h3 id="_pullallarray-values"><code>_.pullAll(array, values)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7555 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pullall "查看Npm包") [&#x24C9;][1]

移除数组中指定的所有元素，接受参数为数组
<br>
**提示:** 不同于 `_.difference`, 这个方法使数组发生变化.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: 修改的数组
2. `values` *(Array)*: 移除的值

#### 返回结果
*(Array)*: 返回的数组

####示例
```js
var array = ['a', 'b', 'c', 'a', 'b', 'c'];

_.pullAll(array, ['a', 'c']);
console.log(array);
// => ['b', 'b']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_pullallbyarray-values-iteratee_identity"><code>_.pullAllBy(array, values, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7585 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pullallby "查看Npm包") [&#x24C9;][1]

This method is like `_.pullAll` except that it accepts `iteratee` which is
invoked for each element of `array` and `values` to generate the criterion
by which they're compared. The iteratee is invoked with one argument: *(value)*.
<br>
<br>
**提示:** 不同于 `_.differenceBy`, this method mutates `array`.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to modify.
2. `values` *(Array)*: The values to remove.
3. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(Array)*: Returns `array`.

####示例
```js
var array = [{ 'x': 1 }, { 'x': 2 }, { 'x': 3 }, { 'x': 1 }];

_.pullAllBy(array, [{ 'x': 1 }, { 'x': 3 }], 'x');
console.log(array);
// => [{ 'x': 2 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_pullallwitharray-values-comparator"><code>_.pullAllWith(array, values, [comparator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7614 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pullallwith "查看Npm包") [&#x24C9;][1]

This method is like `_.pullAll` except that it accepts `comparator` which
is invoked to compare elements of `array` to `values`. The comparator is
invoked with two arguments: *(arrVal, othVal)*.
<br>
<br>
**提示:** 不同于 `_.differenceWith`, this method mutates `array`.

#### 起始版本
4.6.0
#### 参数
1. `array` *(Array)*: The array to modify.
2. `values` *(Array)*: The values to remove.
3. `[comparator]` *(Function)*: The comparator invoked per element.

#### 返回结果
*(Array)*: Returns `array`.

####示例
```js
var array = [{ 'x': 1, 'y': 2 }, { 'x': 3, 'y': 4 }, { 'x': 5, 'y': 6 }];

_.pullAllWith(array, [{ 'x': 3, 'y': 4 }], _.isEqual);
console.log(array);
// => [{ 'x': 1, 'y': 2 }, { 'x': 5, 'y': 6 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_pullatarray-indexes"><code>_.pullAt(array, [indexes])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7644 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pullat "查看Npm包") [&#x24C9;][1]

Removes elements from `array` corresponding to `indexes` and returns an
array of removed elements.
<br>
<br>
**提示:** 不同于 `_.at`, this method mutates `array`.

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: The array to modify.
2. `[indexes]` *(...(number|number&#91;&#93;))*: The indexes of elements to remove.

#### 返回结果
*(Array)*: Returns the new array of removed elements.

####示例
```js
var array = ['a', 'b', 'c', 'd'];
var pulled = _.pullAt(array, [1, 3]);

console.log(array);
// => ['a', 'c']

console.log(pulled);
// => ['b', 'd']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_removearray-predicate_identity"><code>_.remove(array, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7684 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.remove "查看Npm包") [&#x24C9;][1]

Removes all elements from `array` that `predicate` returns truthy for
and returns an array of the removed elements. The predicate is invoked
with three arguments: *(value, index, array)*.
<br>
<br>
**提示:** 不同于 `_.filter`, this method mutates `array`. Use `_.pull`
to pull elements from an array by value.

#### 起始版本
2.0.0
#### 参数
1. `array` *(Array)*: The array to modify.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the new array of removed elements.

####示例
```js
var array = [1, 2, 3, 4];
var evens = _.remove(array, function(n) {
  return n % 2 == 0;
});

console.log(array);
// => [1, 3]

console.log(evens);
// => [2, 4]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_reversearray"><code>_.reverse(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7728 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.reverse "查看Npm包") [&#x24C9;][1]

Reverses `array` so that the first element becomes the last, the second
element becomes the second to last, and so on.
<br>
<br>
**提示:** This method mutates `array` and is based on
[`Array#reverse`](https://mdn.io/Array/reverse).

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to modify.

#### 返回结果
*(Array)*: Returns `array`.

####示例
```js
var array = [1, 2, 3];

_.reverse(array);
// => [3, 2, 1]

console.log(array);
// => [3, 2, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_slicearray-start0-endarraylength"><code>_.slice(array, [start=0], [end=array.length])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7748 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.slice "查看Npm包") [&#x24C9;][1]

Creates a slice of `array` from `start` up to, but not including, `end`.
<br>
<br>
**提示:** This method is used instead of
[`Array#slice`](https://mdn.io/Array/slice) to ensure dense arrays are
returned.

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: The array to slice.
2. `[start=0]` *(number)*: The start position.
3. `[end=array.length]` *(number)*: The end position.

#### 返回结果
*(Array)*: Returns the slice of `array`.

---

<!-- /div -->

<!-- div -->

<h3 id="_sortedindexarray-value"><code>_.sortedIndex(array, value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7781 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sortedindex "查看Npm包") [&#x24C9;][1]

Uses a binary search to determine the lowest index at which `value`
should be inserted into `array` in order to maintain its sort order.

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: The sorted array to inspect.
2. `value` *(&#42;)*: The value to evaluate.

#### 返回结果
*(number)*: Returns the index at which `value` should be inserted into `array`.

####示例
```js
_.sortedIndex([30, 50], 40);
// => 1
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sortedindexbyarray-value-iteratee_identity"><code>_.sortedIndexBy(array, value, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7811 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sortedindexby "查看Npm包") [&#x24C9;][1]

This method is like `_.sortedIndex` except that it accepts `iteratee`
which is invoked for `value` and each element of `array` to compute their
sort ranking. The iteratee is invoked with one argument: *(value)*.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The sorted array to inspect.
2. `value` *(&#42;)*: The value to evaluate.
3. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(number)*: Returns the index at which `value` should be inserted into `array`.

####示例
```js
var objects = [{ 'x': 4 }, { 'x': 5 }];

_.sortedIndexBy(objects, { 'x': 4 }, function(o) { return o.x; });
// => 0

// The `_.property` 的缩写
_.sortedIndexBy(objects, { 'x': 4 }, 'x');
// => 0
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sortedindexofarray-value"><code>_.sortedIndexOf(array, value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7831 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sortedindexof "查看Npm包") [&#x24C9;][1]

This method is like `_.indexOf` except that it performs a binary
search on a sorted `array`.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to inspect.
2. `value` *(&#42;)*: The value to search for.

#### 返回结果
*(number)*: Returns the index of the matched value, else `-1`.

####示例
```js
_.sortedIndexOf([4, 5, 5, 5, 6], 5);
// => 1
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sortedlastindexarray-value"><code>_.sortedLastIndex(array, value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7860 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sortedlastindex "查看Npm包") [&#x24C9;][1]

This method is like `_.sortedIndex` except that it returns the highest
index at which `value` should be inserted into `array` in order to
maintain its sort order.

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: The sorted array to inspect.
2. `value` *(&#42;)*: The value to evaluate.

#### 返回结果
*(number)*: Returns the index at which `value` should be inserted into `array`.

####示例
```js
_.sortedLastIndex([4, 5, 5, 5, 6], 5);
// => 4
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sortedlastindexbyarray-value-iteratee_identity"><code>_.sortedLastIndexBy(array, value, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7890 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sortedlastindexby "查看Npm包") [&#x24C9;][1]

This method is like `_.sortedLastIndex` except that it accepts `iteratee`
which is invoked for `value` and each element of `array` to compute their
sort ranking. The iteratee is invoked with one argument: *(value)*.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The sorted array to inspect.
2. `value` *(&#42;)*: The value to evaluate.
3. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(number)*: Returns the index at which `value` should be inserted into `array`.

####示例
```js
var objects = [{ 'x': 4 }, { 'x': 5 }];

_.sortedLastIndexBy(objects, { 'x': 4 }, function(o) { return o.x; });
// => 1

// The `_.property` 的缩写
_.sortedLastIndexBy(objects, { 'x': 4 }, 'x');
// => 1
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sortedlastindexofarray-value"><code>_.sortedLastIndexOf(array, value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7910 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sortedlastindexof "查看Npm包") [&#x24C9;][1]

This method is like `_.lastIndexOf` except that it performs a binary
search on a sorted `array`.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to inspect.
2. `value` *(&#42;)*: The value to search for.

#### 返回结果
*(number)*: Returns the index of the matched value, else `-1`.

####示例
```js
_.sortedLastIndexOf([4, 5, 5, 5, 6], 5);
// => 3
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sorteduniqarray"><code>_.sortedUniq(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7936 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sorteduniq "查看Npm包") [&#x24C9;][1]

This method is like `_.uniq` except that it's designed and optimized
for sorted arrays.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to inspect.

#### 返回结果
*(Array)*: Returns the new duplicate free array.

####示例
```js
_.sortedUniq([1, 1, 2]);
// => [1, 2]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sorteduniqbyarray-iteratee"><code>_.sortedUniqBy(array, [iteratee])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7958 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sorteduniqby "查看Npm包") [&#x24C9;][1]

This method is like `_.uniqBy` except that it's designed and optimized
for sorted arrays.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to inspect.
2. `[iteratee]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(Array)*: Returns the new duplicate free array.

####示例
```js
_.sortedUniqBy([1.1, 1.2, 2.3, 2.4], Math.floor);
// => [1.1, 2.3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tailarray"><code>_.tail(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L7978 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tail "查看Npm包") [&#x24C9;][1]

Gets all but the first element of `array`.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to query.

#### 返回结果
*(Array)*: Returns the slice of `array`.

####示例
```js
_.tail([1, 2, 3]);
// => [2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_takearray-n1"><code>_.take(array, [n=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8008 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.take "查看Npm包") [&#x24C9;][1]

Creates a slice of `array` with `n` elements taken from the beginning.

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: The array to query.
2. `[n=1]` *(number)*: The number of elements to take.

#### 返回结果
*(Array)*: Returns the slice of `array`.

####示例
```js
_.take([1, 2, 3]);
// => [1]

_.take([1, 2, 3], 2);
// => [1, 2]

_.take([1, 2, 3], 5);
// => [1, 2, 3]

_.take([1, 2, 3], 0);
// => []
```
---

<!-- /div -->

<!-- div -->

<h3 id="_takerightarray-n1"><code>_.takeRight(array, [n=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8041 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.takeright "查看Npm包") [&#x24C9;][1]

Creates a slice of `array` with `n` elements taken from the end.

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: The array to query.
2. `[n=1]` *(number)*: The number of elements to take.

#### 返回结果
*(Array)*: Returns the slice of `array`.

####示例
```js
_.takeRight([1, 2, 3]);
// => [3]

_.takeRight([1, 2, 3], 2);
// => [2, 3]

_.takeRight([1, 2, 3], 5);
// => [1, 2, 3]

_.takeRight([1, 2, 3], 0);
// => []
```
---

<!-- /div -->

<!-- div -->

<h3 id="_takerightwhilearray-predicate_identity"><code>_.takeRightWhile(array, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8087 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.takerightwhile "查看Npm包") [&#x24C9;][1]

Creates a slice of `array` with elements taken from the end. Elements are
taken until `predicate` returns falsey. The predicate is invoked with
three arguments: *(value, index, array)*.

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: The array to query.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the slice of `array`.

####示例
```js
var users = [
  { 'user': 'barney',  'active': true },
  { 'user': 'fred',    'active': false },
  { 'user': 'pebbles', 'active': false }
];

_.takeRightWhile(users, function(o) { return !o.active; });
// => objects for ['fred', 'pebbles']

// The `_.matches` 的缩写
_.takeRightWhile(users, { 'user': 'pebbles', 'active': false });
// => objects for ['pebbles']

// The `_.matchesProperty` 的缩写
_.takeRightWhile(users, ['active', false]);
// => objects for ['fred', 'pebbles']

// The `_.property` 的缩写
_.takeRightWhile(users, 'active');
// => []
```
---

<!-- /div -->

<!-- div -->

<h3 id="_takewhilearray-predicate_identity"><code>_.takeWhile(array, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8129 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.takewhile "查看Npm包") [&#x24C9;][1]

Creates a slice of `array` with elements taken from the beginning. Elements
are taken until `predicate` returns falsey. The predicate is invoked with
three arguments: *(value, index, array)*.

#### 起始版本
3.0.0
#### 参数
1. `array` *(Array)*: The array to query.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the slice of `array`.

####示例
```js
var users = [
  { 'user': 'barney',  'active': false },
  { 'user': 'fred',    'active': false},
  { 'user': 'pebbles', 'active': true }
];

_.takeWhile(users, function(o) { return !o.active; });
// => objects for ['barney', 'fred']

// The `_.matches` 的缩写
_.takeWhile(users, { 'user': 'barney', 'active': false });
// => objects for ['barney']

// The `_.matchesProperty` 的缩写
_.takeWhile(users, ['active', false]);
// => objects for ['barney', 'fred']

// The `_.property` 的缩写
_.takeWhile(users, 'active');
// => []
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unionarrays"><code>_.union([arrays])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8151 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.union "查看Npm包") [&#x24C9;][1]

Creates an array of unique values, in order, from all given arrays using
[`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)
for equality comparisons.

#### 起始版本
0.1.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to inspect.

#### 返回结果
*(Array)*: Returns the new array of combined values.

####示例
```js
_.union([2], [1, 2]);
// => [2, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unionbyarrays-iteratee_identity"><code>_.unionBy([arrays], [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8179 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.unionby "查看Npm包") [&#x24C9;][1]

This method is like `_.union` except that it accepts `iteratee` which is
invoked for each element of each `arrays` to generate the criterion by
which uniqueness is computed. Result values are chosen from the first
array in which the value occurs. The iteratee is invoked with one argument:<br>
*(value)*.

#### 起始版本
4.0.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to inspect.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(Array)*: Returns the new array of combined values.

####示例
```js
_.unionBy([2.1], [1.2, 2.3], Math.floor);
// => [2.1, 1.2]

// The `_.property` 的缩写
_.unionBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 1 }, { 'x': 2 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unionwitharrays-comparator"><code>_.unionWith([arrays], [comparator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8208 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.unionwith "查看Npm包") [&#x24C9;][1]

This method is like `_.union` except that it accepts `comparator` which
is invoked to compare elements of `arrays`. Result values are chosen from
the first array in which the value occurs. The comparator is invoked
with two arguments: *(arrVal, othVal)*.

#### 起始版本
4.0.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to inspect.
2. `[comparator]` *(Function)*: The comparator invoked per element.

#### 返回结果
*(Array)*: Returns the new array of combined values.

####示例
```js
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.unionWith(objects, others, _.isEqual);
// => [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }, { 'x': 1, 'y': 1 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_uniqarray"><code>_.uniq(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8234 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.uniq "查看Npm包") [&#x24C9;][1]

Creates a duplicate-free version of an array, using
[`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)
for equality comparisons, in which only the first occurrence of each element
is kept. The order of result values is determined by the order they occur
in the array.

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: The array to inspect.

#### 返回结果
*(Array)*: Returns the new duplicate free array.

####示例
```js
_.uniq([2, 1, 2]);
// => [2, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_uniqbyarray-iteratee_identity"><code>_.uniqBy(array, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8264 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.uniqby "查看Npm包") [&#x24C9;][1]

This method is like `_.uniq` except that it accepts `iteratee` which is
invoked for each element in `array` to generate the criterion by which
uniqueness is computed. The order of result values is determined by the
order they occur in the array. The iteratee is invoked with one argument:<br>
*(value)*.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to inspect.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(Array)*: Returns the new duplicate free array.

####示例
```js
_.uniqBy([2.1, 1.2, 2.3], Math.floor);
// => [2.1, 1.2]

// The `_.property` 的缩写
_.uniqBy([{ 'x': 1 }, { 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 1 }, { 'x': 2 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_uniqwitharray-comparator"><code>_.uniqWith(array, [comparator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8290 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.uniqwith "查看Npm包") [&#x24C9;][1]

This method is like `_.uniq` except that it accepts `comparator` which
is invoked to compare elements of `array`. The order of result values is
determined by the order they occur in the array.The comparator is invoked
with two arguments: *(arrVal, othVal)*.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to inspect.
2. `[comparator]` *(Function)*: The comparator invoked per element.

#### 返回结果
*(Array)*: Returns the new duplicate free array.

####示例
```js
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.uniqWith(objects, _.isEqual);
// => [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unziparray"><code>_.unzip(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8315 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.unzip "查看Npm包") [&#x24C9;][1]

This method is like `_.zip` except that it accepts an array of grouped
elements and creates an array regrouping the elements to their pre-zip
configuration.

#### 起始版本
1.2.0
#### 参数
1. `array` *(Array)*: The array of grouped elements to process.

#### 返回结果
*(Array)*: Returns the new array of regrouped elements.

####示例
```js
var zipped = _.zip(['a', 'b'], [1, 2], [true, false]);
// => [['a', 1, true], ['b', 2, false]]

_.unzip(zipped);
// => [['a', 'b'], [1, 2], [true, false]]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unzipwitharray-iteratee_identity"><code>_.unzipWith(array, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8352 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.unzipwith "查看Npm包") [&#x24C9;][1]

This method is like `_.unzip` except that it accepts `iteratee` to specify
how regrouped values should be combined. The iteratee is invoked with the
elements of each group: *(...group)*.

#### 起始版本
3.8.0
#### 参数
1. `array` *(Array)*: The array of grouped elements to process.
2. `[iteratee=_.identity]` *(Function)*: The function to combine regrouped values.

#### 返回结果
*(Array)*: Returns the new array of regrouped elements.

####示例
```js
var zipped = _.zip([1, 2], [10, 20], [100, 200]);
// => [[1, 10, 100], [2, 20, 200]]

_.unzipWith(zipped, _.add);
// => [3, 30, 300]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_withoutarray-values"><code>_.without(array, [values])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8385 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.without "查看Npm包") [&#x24C9;][1]

Creates an array excluding all given values using
[`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)
for equality comparisons.
<br>
<br>
**提示:** 不同于 `_.pull`, 这个方法返回新的数组．

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: The array to inspect.
2. `[values]` *(...&#42;)*: The values to exclude.

#### 返回结果
*(Array)*: Returns the new array of filtered values.

####示例
```js
_.without([2, 1, 2, 3], 1, 2);
// => [3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_xorarrays"><code>_.xor([arrays])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8409 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.xor "查看Npm包") [&#x24C9;][1]

Creates an array of unique values that is the
[symmetric difference](https://en.wikipedia.org/wiki/Symmetric_difference)
of the given arrays. The order of result values is determined by the order
they occur in the arrays.

#### 起始版本
2.4.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to inspect.

#### 返回结果
*(Array)*: Returns the new array of filtered values.

####示例
```js
_.xor([2, 1], [2, 3]);
// => [1, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_xorbyarrays-iteratee_identity"><code>_.xorBy([arrays], [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8437 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.xorby "查看Npm包") [&#x24C9;][1]

This method is like `_.xor` except that it accepts `iteratee` which is
invoked for each element of each `arrays` to generate the criterion by
which by which they're compared. The order of result values is determined
by the order they occur in the arrays. The iteratee is invoked with one
argument: *(value)*.

#### 起始版本
4.0.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to inspect.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(Array)*: Returns the new array of filtered values.

####示例
```js
_.xorBy([2.1, 1.2], [2.3, 3.4], Math.floor);
// => [1.2, 3.4]

// The `_.property` 的缩写
_.xorBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
// => [{ 'x': 2 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_xorwitharrays-comparator"><code>_.xorWith([arrays], [comparator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8466 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.xorwith "查看Npm包") [&#x24C9;][1]

This method is like `_.xor` except that it accepts `comparator` which is
invoked to compare elements of `arrays`. The order of result values is
determined by the order they occur in the arrays. The comparator is invoked
with two arguments: *(arrVal, othVal)*.

#### 起始版本
4.0.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to inspect.
2. `[comparator]` *(Function)*: The comparator invoked per element.

#### 返回结果
*(Array)*: Returns the new array of filtered values.

####示例
```js
var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];

_.xorWith(objects, others, _.isEqual);
// => [{ 'x': 2, 'y': 1 }, { 'x': 1, 'y': 1 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ziparrays"><code>_.zip([arrays])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8490 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.zip "查看Npm包") [&#x24C9;][1]

Creates an array of grouped elements, the first of which contains the
first elements of the given arrays, the second of which contains the
second elements of the given arrays, and so on.

#### 起始版本
0.1.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to process.

#### 返回结果
*(Array)*: Returns the new array of grouped elements.

####示例
```js
_.zip(['a', 'b'], [1, 2], [true, false]);
// => [['a', 1, true], ['b', 2, false]]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_zipobjectprops-values"><code>_.zipObject([props=[]], [values=[]])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8508 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.zipobject "查看Npm包") [&#x24C9;][1]

This method is like `_.fromPairs` except that it accepts two arrays,
one of property identifiers and one of corresponding values.

#### 起始版本
0.4.0
#### 参数
1. `[props=[]]` *(Array)*: The property identifiers.
2. `[values=[]]` *(Array)*: The property values.

#### 返回结果
*(Object)*: Returns the new object.

####示例
```js
_.zipObject(['a', 'b'], [1, 2]);
// => { 'a': 1, 'b': 2 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_zipobjectdeepprops-values"><code>_.zipObjectDeep([props=[]], [values=[]])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8527 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.zipobjectdeep "查看Npm包") [&#x24C9;][1]

This method is like `_.zipObject` except that it supports property paths.

#### 起始版本
4.1.0
#### 参数
1. `[props=[]]` *(Array)*: The property identifiers.
2. `[values=[]]` *(Array)*: The property values.

#### 返回结果
*(Object)*: Returns the new object.

####示例
```js
_.zipObjectDeep(['a.b[0].c', 'a.b[1].d'], [1, 2]);
// => { 'a': { 'b': [{ 'c': 1 }, { 'd': 2 }] } }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_zipwitharrays-iteratee_identity"><code>_.zipWith([arrays], [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8550 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.zipwith "查看Npm包") [&#x24C9;][1]

This method is like `_.zip` except that it accepts `iteratee` to specify
how grouped values should be combined. The iteratee is invoked with the
elements of each group: *(...group)*.

#### 起始版本
3.8.0
#### 参数
1. `[arrays]` *(...Array)*: The arrays to process.
2. `[iteratee=_.identity]` *(Function)*: The function to combine grouped values.

#### 返回结果
*(Array)*: Returns the new array of grouped elements.

####示例
```js
_.zipWith([1, 2], [10, 20], [100, 200], function(a, b, c) {
  return a + b + c;
});
// => [111, 222]
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Collection” Methods`

<!-- div -->

<h3 id="_countbycollection-iteratee_identity"><code>_.countBy(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8930 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.countby "查看Npm包") [&#x24C9;][1]

Creates an object composed of keys generated from the results of running
each element of `collection` thru `iteratee`. The corresponding value of
each key is the number of times the key was returned by `iteratee`. The
iteratee is invoked with one argument: *(value)*.

#### 起始版本
0.5.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The iteratee to transform keys.

#### 返回结果
*(Object)*: Returns the composed aggregate object.

####示例
```js
_.countBy([6.1, 4.2, 6.3], Math.floor);
// => { '4': 1, '6': 2 }

// The `_.property` 的缩写
_.countBy(['one', 'two', 'three'], 'length');
// => { '3': 2, '5': 1 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_everycollection-predicate_identity"><code>_.every(collection, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8980 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.every "查看Npm包") [&#x24C9;][1]

Checks if `predicate` returns truthy for **all** elements of `collection`.
Iteration is stopped once `predicate` returns falsey. The predicate is
invoked with three arguments: *(value, index|key, collection)*.
<br>
<br>
**提示:** This method returns `true` for
[empty collections](https://en.wikipedia.org/wiki/Empty_set) because
[everything is true](https://en.wikipedia.org/wiki/Vacuous_truth) of
elements of empty collections.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(boolean)*: Returns `true` if all elements pass the predicate check, else `false`.

####示例
```js
_.every([true, 1, null, 'yes'], Boolean);
// => false

var users = [
  { 'user': 'barney', 'age': 36, 'active': false },
  { 'user': 'fred',   'age': 40, 'active': false }
];

// The `_.matches` 的缩写
_.every(users, { 'user': 'barney', 'active': false });
// => false

// The `_.matchesProperty` 的缩写
_.every(users, ['active', false]);
// => true

// The `_.property` 的缩写
_.every(users, 'active');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_filtercollection-predicate_identity"><code>_.filter(collection, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9026 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.filter "查看Npm包") [&#x24C9;][1]

Iterates over elements of `collection`, returning an array of all elements
`predicate` returns truthy for. The predicate is invoked with three
arguments: *(value, index|key, collection)*.
<br>
<br>
**提示:** 不同于 `_.remove`, 这个方法返回新的数组．

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the new filtered array.

####示例
```js
var users = [
  { 'user': 'barney', 'age': 36, 'active': true },
  { 'user': 'fred',   'age': 40, 'active': false }
];

_.filter(users, function(o) { return !o.active; });
// => objects for ['fred']

// The `_.matches` 的缩写
_.filter(users, { 'age': 36, 'active': true });
// => objects for ['barney']

// The `_.matchesProperty` 的缩写
_.filter(users, ['active', false]);
// => objects for ['fred']

// The `_.property` 的缩写
_.filter(users, 'active');
// => objects for ['barney']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_findcollection-predicate_identity-fromindex0"><code>_.find(collection, [predicate=_.identity], [fromIndex=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9068 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.find "查看Npm包") [&#x24C9;][1]

Iterates over elements of `collection`, returning the first element
`predicate` returns truthy for. The predicate is invoked with three
arguments: *(value, index|key, collection)*.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to inspect.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.
3. `[fromIndex=0]` *(number)*: The index to search from.

#### 返回结果
*(&#42;)*: Returns the matched element, else `undefined`.

####示例
```js
var users = [
  { 'user': 'barney',  'age': 36, 'active': true },
  { 'user': 'fred',    'age': 40, 'active': false },
  { 'user': 'pebbles', 'age': 1,  'active': true }
];

_.find(users, function(o) { return o.age < 40; });
// => object for 'barney'

// The `_.matches` 的缩写
_.find(users, { 'age': 1, 'active': true });
// => object for 'pebbles'

// The `_.matchesProperty` 的缩写
_.find(users, ['active', false]);
// => object for 'fred'

// The `_.property` 的缩写
_.find(users, 'active');
// => object for 'barney'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_findlastcollection-predicate_identity-fromindexcollectionlength-1"><code>_.findLast(collection, [predicate=_.identity], [fromIndex=collection.length-1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9090 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.findlast "查看Npm包") [&#x24C9;][1]

This method is like `_.find` except that it iterates over elements of
`collection` from right to left.

#### 起始版本
2.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to inspect.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.
3. `[fromIndex=collection.length-1]` *(number)*: The index to search from.

#### 返回结果
*(&#42;)*: Returns the matched element, else `undefined`.

####示例
```js
_.findLast([1, 2, 3, 4], function(n) {
  return n % 2 == 1;
});
// => 3
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flatmapcollection-iteratee_identity"><code>_.flatMap(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9114 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flatmap "查看Npm包") [&#x24C9;][1]

Creates a flattened array of values by running each element in `collection`
thru `iteratee` and flattening the mapped results. The iteratee is invoked
with three arguments: *(value, index|key, collection)*.

#### 起始版本
4.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the new flattened array.

####示例
```js
function duplicate(n) {
  return [n, n];
}

_.flatMap([1, 2], duplicate);
// => [1, 1, 2, 2]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flatmapdeepcollection-iteratee_identity"><code>_.flatMapDeep(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9139 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flatmapdeep "查看Npm包") [&#x24C9;][1]

This method is like `_.flatMap` except that it recursively flattens the
mapped results.

#### 起始版本
4.7.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the new flattened array.

####示例
```js
function duplicate(n) {
  return [[[n, n]]];
}

_.flatMapDeep([1, 2], duplicate);
// => [1, 1, 2, 2]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flatmapdepthcollection-iteratee_identity-depth1"><code>_.flatMapDepth(collection, [iteratee=_.identity], [depth=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9165 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flatmapdepth "查看Npm包") [&#x24C9;][1]

This method is like `_.flatMap` except that it recursively flattens the
mapped results up to `depth` times.

#### 起始版本
4.7.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.
3. `[depth=1]` *(number)*: The maximum recursion depth.

#### 返回结果
*(Array)*: Returns the new flattened array.

####示例
```js
function duplicate(n) {
  return [[[n, n]]];
}

_.flatMapDepth([1, 2], duplicate, 2);
// => [[1, 1], [2, 2]]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_foreachcollection-iteratee_identity"><code>_.forEach(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9200 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.foreach "查看Npm包") [&#x24C9;][1]

Iterates over elements of `collection` and invokes `iteratee` for each element.
The iteratee is invoked with three arguments: *(value, index|key, collection)*.
Iteratee functions may exit iteration early by explicitly returning `false`.
<br>
<br>
**提示:** As with other "Collections" methods, objects with a "length"
property are iterated like arrays. To avoid this behavior use `_.forIn`
or `_.forOwn` for object iteration.

#### 起始版本
0.1.0
#### Aliases
*_.each*

#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(&#42;)*: Returns `collection`.

####示例
```js
_.forEach([1, 2], function(value) {
  console.log(value);
});
// => Logs `1` then `2`.

_.forEach({ 'a': 1, 'b': 2 }, function(value, key) {
  console.log(key);
});
// => Logs 'a' then 'b' (iteration order is not guaranteed).
```
---

<!-- /div -->

<!-- div -->

<h3 id="_foreachrightcollection-iteratee_identity"><code>_.forEachRight(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9225 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.foreachright "查看Npm包") [&#x24C9;][1]

This method is like `_.forEach` except that it iterates over elements of
`collection` from right to left.

#### 起始版本
2.0.0
#### Aliases
*_.eachRight*

#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(&#42;)*: Returns `collection`.

####示例
```js
_.forEachRight([1, 2], function(value) {
  console.log(value);
});
// => Logs `2` then `1`.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_groupbycollection-iteratee_identity"><code>_.groupBy(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9254 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.groupby "查看Npm包") [&#x24C9;][1]

Creates an object composed of keys generated from the results of running
each element of `collection` thru `iteratee`. The order of grouped values
is determined by the order they occur in `collection`. The corresponding
value of each key is an array of elements responsible for generating the
key. The iteratee is invoked with one argument: *(value)*.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The iteratee to transform keys.

#### 返回结果
*(Object)*: Returns the composed aggregate object.

####示例
```js
_.groupBy([6.1, 4.2, 6.3], Math.floor);
// => { '4': [4.2], '6': [6.1, 6.3] }

// The `_.property` 的缩写
_.groupBy(['one', 'two', 'three'], 'length');
// => { '3': ['one', 'two'], '5': ['three'] }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_includescollection-value-fromindex0"><code>_.includes(collection, value, [fromIndex=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9292 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.includes "查看Npm包") [&#x24C9;][1]

Checks if `value` is in `collection`. If `collection` is a string, it's
checked for a substring of `value`, otherwise
[`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)
is used for equality comparisons. If `fromIndex` is negative, it's used as
the offset from the end of `collection`.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object|string)*: The collection to inspect.
2. `value` *(&#42;)*: The value to search for.
3. `[fromIndex=0]` *(number)*: The index to search from.

#### 返回结果
*(boolean)*: Returns `true` if `value` is found, else `false`.

####示例
```js
_.includes([1, 2, 3], 1);
// => true

_.includes([1, 2, 3], 1, 2);
// => false

_.includes({ 'a': 1, 'b': 2 }, 1);
// => true

_.includes('abcd', 'bc');
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_invokemapcollection-path-args"><code>_.invokeMap(collection, path, [args])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9328 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.invokemap "查看Npm包") [&#x24C9;][1]

Invokes the method at `path` of each element in `collection`, returning
an array of the results of each invoked method. Any additional arguments
are provided to each invoked method. If `path` is a function, it's invoked
for, and `this` bound to, each element in `collection`.

#### 起始版本
4.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `path` *(Array|Function|string)*: The path of the method to invoke or the function invoked per iteration.
3. `[args]` *(...&#42;)*: The arguments to invoke each method with.

#### 返回结果
*(Array)*: Returns the array of results.

####示例
```js
_.invokeMap([[5, 1, 7], [3, 2, 1]], 'sort');
// => [[1, 5, 7], [1, 2, 3]]

_.invokeMap([123, 456], String.prototype.split, '');
// => [['1', '2', '3'], ['4', '5', '6']]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_keybycollection-iteratee_identity"><code>_.keyBy(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9370 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.keyby "查看Npm包") [&#x24C9;][1]

Creates an object composed of keys generated from the results of running
each element of `collection` thru `iteratee`. The corresponding value of
each key is the last element responsible for generating the key. The
iteratee is invoked with one argument: *(value)*.

#### 起始版本
4.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The iteratee to transform keys.

#### 返回结果
*(Object)*: Returns the composed aggregate object.

####示例
```js
var array = [
  { 'dir': 'left', 'code': 97 },
  { 'dir': 'right', 'code': 100 }
];

_.keyBy(array, function(o) {
  return String.fromCharCode(o.code);
});
// => { 'a': { 'dir': 'left', 'code': 97 }, 'd': { 'dir': 'right', 'code': 100 } }

_.keyBy(array, 'dir');
// => { 'left': { 'dir': 'left', 'code': 97 }, 'right': { 'dir': 'right', 'code': 100 } }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_mapcollection-iteratee_identity"><code>_.map(collection, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9416 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.map "查看Npm包") [&#x24C9;][1]

Creates an array of values by running each element in `collection` thru
`iteratee`. The iteratee is invoked with three arguments:<br>
*(value, index|key, collection)*.
<br>
<br>
Many lodash methods are guarded to work as iteratees for methods like
`_.every`, `_.filter`, `_.map`, `_.mapValues`, `_.reject`, and `_.some`.
<br>
<br>
The guarded methods are:<br>
`ary`, `chunk`, `curry`, `curryRight`, `drop`, `dropRight`, `every`,
`fill`, `invert`, `parseInt`, `random`, `range`, `rangeRight`, `repeat`,
`sampleSize`, `slice`, `some`, `sortBy`, `split`, `take`, `takeRight`,
`template`, `trim`, `trimEnd`, `trimStart`, and `words`

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the new mapped array.

####示例
```js
function square(n) {
  return n * n;
}

_.map([4, 8], square);
// => [16, 64]

_.map({ 'a': 4, 'b': 8 }, square);
// => [16, 64] (iteration order is not guaranteed)

var users = [
  { 'user': 'barney' },
  { 'user': 'fred' }
];

// The `_.property` 的缩写
_.map(users, 'user');
// => ['barney', 'fred']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_orderbycollection-iteratees_identity-orders"><code>_.orderBy(collection, [iteratees=[_.identity]], [orders])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9450 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.orderby "查看Npm包") [&#x24C9;][1]

This method is like `_.sortBy` except that it allows specifying the sort
orders of the iteratees to sort by. If `orders` is unspecified, all values
are sorted in ascending order. Otherwise, specify an order of "desc" for
descending or "asc" for ascending sort order of corresponding values.

#### 起始版本
4.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratees=[_.identity]]` *(Array&#91;&#93;|Function&#91;&#93;|Object&#91;&#93;|string&#91;&#93;)*: The iteratees to sort by.
3. `[orders]` *(string&#91;&#93;)*: The sort orders of `iteratees`.

#### 返回结果
*(Array)*: Returns the new sorted array.

####示例
```js
var users = [
  { 'user': 'fred',   'age': 48 },
  { 'user': 'barney', 'age': 34 },
  { 'user': 'fred',   'age': 40 },
  { 'user': 'barney', 'age': 36 }
];

// Sort by `user` in ascending order and by `age` in descending order.
_.orderBy(users, ['user', 'age'], ['asc', 'desc']);
// => objects for [['barney', 36], ['barney', 34], ['fred', 48], ['fred', 40]]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_partitioncollection-predicate_identity"><code>_.partition(collection, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9500 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.partition "查看Npm包") [&#x24C9;][1]

Creates an array of elements split into two groups, the first of which
contains elements `predicate` returns truthy for, the second of which
contains elements `predicate` returns falsey for. The predicate is
invoked with one argument: *(value)*.

#### 起始版本
3.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the array of grouped elements.

####示例
```js
var users = [
  { 'user': 'barney',  'age': 36, 'active': false },
  { 'user': 'fred',    'age': 40, 'active': true },
  { 'user': 'pebbles', 'age': 1,  'active': false }
];

_.partition(users, function(o) { return o.active; });
// => objects for [['fred'], ['barney', 'pebbles']]

// The `_.matches` 的缩写
_.partition(users, { 'age': 1, 'active': false });
// => objects for [['pebbles'], ['barney', 'fred']]

// The `_.matchesProperty` 的缩写
_.partition(users, ['active', false]);
// => objects for [['barney', 'pebbles'], ['fred']]

// The `_.property` 的缩写
_.partition(users, 'active');
// => objects for [['fred'], ['barney', 'pebbles']]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_reducecollection-iteratee_identity-accumulator"><code>_.reduce(collection, [iteratee=_.identity], [accumulator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9541 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.reduce "查看Npm包") [&#x24C9;][1]

Reduces `collection` to a value which is the accumulated result of running
each element in `collection` thru `iteratee`, where each successive
invocation is supplied the return value of the previous. If `accumulator`
is not given, the first element of `collection` is used as the initial
value. The iteratee is invoked with four arguments:<br>
*(accumulator, value, index|key, collection)*.
<br>
<br>
Many lodash methods are guarded to work as iteratees for methods like
`_.reduce`, `_.reduceRight`, and `_.transform`.
<br>
<br>
The guarded methods are:<br>
`assign`, `defaults`, `defaultsDeep`, `includes`, `merge`, `orderBy`,
and `sortBy`

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.
3. `[accumulator]` *(&#42;)*: The initial value.

#### 返回结果
*(&#42;)*: Returns the accumulated value.

####示例
```js
_.reduce([1, 2], function(sum, n) {
  return sum + n;
}, 0);
// => 3

_.reduce({ 'a': 1, 'b': 2, 'c': 1 }, function(result, value, key) {
  (result[value] || (result[value] = [])).push(key);
  return result;
}, {});
// => { '1': ['a', 'c'], '2': ['b'] } (iteration order is not guaranteed)
```
---

<!-- /div -->

<!-- div -->

<h3 id="_reducerightcollection-iteratee_identity-accumulator"><code>_.reduceRight(collection, [iteratee=_.identity], [accumulator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9570 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.reduceright "查看Npm包") [&#x24C9;][1]

This method is like `_.reduce` except that it iterates over elements of
`collection` from right to left.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.
3. `[accumulator]` *(&#42;)*: The initial value.

#### 返回结果
*(&#42;)*: Returns the accumulated value.

####示例
```js
var array = [[0, 1], [2, 3], [4, 5]];

_.reduceRight(array, function(flattened, other) {
  return flattened.concat(other);
}, []);
// => [4, 5, 2, 3, 0, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_rejectcollection-predicate_identity"><code>_.reject(collection, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9611 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.reject "查看Npm包") [&#x24C9;][1]

The opposite of `_.filter`; this method returns the elements of `collection`
that `predicate` does **not** return truthy for.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the new filtered array.

####示例
```js
var users = [
  { 'user': 'barney', 'age': 36, 'active': false },
  { 'user': 'fred',   'age': 40, 'active': true }
];

_.reject(users, function(o) { return !o.active; });
// => objects for ['fred']

// The `_.matches` 的缩写
_.reject(users, { 'age': 40, 'active': true });
// => objects for ['barney']

// The `_.matchesProperty` 的缩写
_.reject(users, ['active', false]);
// => objects for ['fred']

// The `_.property` 的缩写
_.reject(users, 'active');
// => objects for ['barney']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_samplecollection"><code>_.sample(collection)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9630 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sample "查看Npm包") [&#x24C9;][1]

Gets a random element from `collection`.

#### 起始版本
2.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to sample.

#### 返回结果
*(&#42;)*: Returns the random element.

####示例
```js
_.sample([1, 2, 3, 4]);
// => 2
```
---

<!-- /div -->

<!-- div -->

<h3 id="_samplesizecollection-n1"><code>_.sampleSize(collection, [n=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9654 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.samplesize "查看Npm包") [&#x24C9;][1]

Gets `n` random elements at unique keys from `collection` up to the
size of `collection`.

#### 起始版本
4.0.0
#### 参数
1. `collection` *(Array|Object)*: The collection to sample.
2. `[n=1]` *(number)*: The number of elements to sample.

#### 返回结果
*(Array)*: Returns the random elements.

####示例
```js
_.sampleSize([1, 2, 3], 2);
// => [3, 1]

_.sampleSize([1, 2, 3], 4);
// => [2, 3, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_shufflecollection"><code>_.shuffle(collection)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9678 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.shuffle "查看Npm包") [&#x24C9;][1]

Creates an array of shuffled values, using a version of the
[Fisher-Yates shuffle](https://en.wikipedia.org/wiki/Fisher-Yates_shuffle).

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to shuffle.

#### 返回结果
*(Array)*: Returns the new shuffled array.

####示例
```js
_.shuffle([1, 2, 3, 4]);
// => [4, 1, 3, 2]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sizecollection"><code>_.size(collection)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9706 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.size "查看Npm包") [&#x24C9;][1]

Gets the size of `collection` by returning its length for array-like
values or the number of own enumerable string keyed properties for objects.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object|string)*: The collection to inspect.

#### 返回结果
*(number)*: Returns the collection size.

####示例
```js
_.size([1, 2, 3]);
// => 3

_.size({ 'a': 1, 'b': 2 });
// => 2

_.size('pebbles');
// => 7
```
---

<!-- /div -->

<!-- div -->

<h3 id="_somecollection-predicate_identity"><code>_.some(collection, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9756 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.some "查看Npm包") [&#x24C9;][1]

Checks if `predicate` returns truthy for **any** element of `collection`.
Iteration is stopped once `predicate` returns truthy. The predicate is
invoked with three arguments: *(value, index|key, collection)*.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(boolean)*: Returns `true` if any element passes the predicate check, else `false`.

####示例
```js
_.some([null, 0, 'yes', false], Boolean);
// => true

var users = [
  { 'user': 'barney', 'active': true },
  { 'user': 'fred',   'active': false }
];

// The `_.matches` 的缩写
_.some(users, { 'user': 'barney', 'active': false });
// => false

// The `_.matchesProperty` 的缩写
_.some(users, ['active', false]);
// => true

// The `_.property` 的缩写
_.some(users, 'active');
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sortbycollection-iteratees_identity"><code>_.sortBy(collection, [iteratees=[_.identity]])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9793 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sortby "查看Npm包") [&#x24C9;][1]

Creates an array of elements, sorted in ascending order by the results of
running each element in a collection thru each iteratee. This method
performs a stable sort, that is, it preserves the original sort order of
equal elements. The iteratees are invoked with one argument: *(value)*.

#### 起始版本
0.1.0
#### 参数
1. `collection` *(Array|Object)*: The collection to iterate over.
2. `[iteratees=[_.identity]]` *(...(Function|Function&#91;&#93;))*: The iteratees to sort by.

#### 返回结果
*(Array)*: Returns the new sorted array.

####示例
```js
var users = [
  { 'user': 'fred',   'age': 48 },
  { 'user': 'barney', 'age': 36 },
  { 'user': 'fred',   'age': 40 },
  { 'user': 'barney', 'age': 34 }
];

_.sortBy(users, [function(o) { return o.user; }]);
// => objects for [['barney', 36], ['barney', 34], ['fred', 48], ['fred', 40]]

_.sortBy(users, ['user', 'age']);
// => objects for [['barney', 34], ['barney', 36], ['fred', 40], ['fred', 48]]
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Date” Methods`

<!-- div -->

<h3 id="_now"><code>_.now()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9824 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.now "查看Npm包") [&#x24C9;][1]

Gets the timestamp of the number of milliseconds that have elapsed since
the Unix epoch *(1 January `1970 00`:00:00 UTC)*.

#### 起始版本
2.4.0
#### 返回结果
*(number)*: Returns the timestamp.

####示例
```js
_.defer(function(stamp) {
  console.log(_.now() - stamp);
}, _.now());
// => Logs the number of milliseconds it took for the deferred invocation.
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Function” Methods`

<!-- div -->

<h3 id="_aftern-func"><code>_.after(n, func)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9854 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.after "查看Npm包") [&#x24C9;][1]

The opposite of `_.before`; this method creates a function that invokes
`func` once it's called `n` or more times.

#### 起始版本
0.1.0
#### 参数
1. `n` *(number)*: The number of calls before `func` is invoked.
2. `func` *(Function)*: The function to restrict.

#### 返回结果
*(Function)*: Returns the new restricted function.

####示例
```js
var saves = ['profile', 'settings'];

var done = _.after(saves.length, function() {
  console.log('done saving!');
});

_.forEach(saves, function(type) {
  asyncSave({ 'type': type, 'complete': done });
});
// => Logs 'done saving!' after the two async saves have completed.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_aryfunc-nfunclength"><code>_.ary(func, [n=func.length])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9883 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.ary "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func`, with up to `n` arguments,
ignoring any additional arguments.

#### 起始版本
3.0.0
#### 参数
1. `func` *(Function)*: The function to cap arguments for.
2. `[n=func.length]` *(number)*: The arity cap.

#### 返回结果
*(Function)*: Returns the new capped function.

####示例
```js
_.map(['6', '8', '10'], _.ary(parseInt, 1));
// => [6, 8, 10]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_beforen-func"><code>_.before(n, func)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9906 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.before "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func`, with the `this` binding and arguments
of the created function, while it's called less than `n` times. Subsequent
calls to the created function return the result of the last `func` invocation.

#### 起始版本
3.0.0
#### 参数
1. `n` *(number)*: The number of calls at which `func` is no longer invoked.
2. `func` *(Function)*: The function to restrict.

#### 返回结果
*(Function)*: Returns the new restricted function.

####示例
```js
jQuery(element).on('click', _.before(5, addContactToList));
// => Allows adding up to 4 contacts to the list.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_bindfunc-thisarg-partials"><code>_.bind(func, thisArg, [partials])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L9958 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.bind "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with the `this` binding of `thisArg`
and `partials` prepended to the arguments it receives.
<br>
<br>
The `_.bind.placeholder` value, which defaults to `_` in monolithic builds,
may be used as a placeholder for partially applied arguments.
<br>
<br>
**提示:** 不同于 native `Function#bind`, this method doesn't set the "length"
property of bound functions.

#### 起始版本
0.1.0
#### 参数
1. `func` *(Function)*: The function to bind.
2. `thisArg` *(&#42;)*: The `this` binding of `func`.
3. `[partials]` *(...&#42;)*: The arguments to be partially applied.

#### 返回结果
*(Function)*: Returns the new bound function.

####示例
```js
function greet(greeting, punctuation) {
  return greeting + ' ' + this.user + punctuation;
}

var object = { 'user': 'fred' };

var bound = _.bind(greet, object, 'hi');
bound('!');
// => 'hi fred!'

// Bound with placeholders.
var bound = _.bind(greet, object, _, '!');
bound('hi');
// => 'hi fred!'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_bindkeyobject-key-partials"><code>_.bindKey(object, key, [partials])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10012 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.bindkey "查看Npm包") [&#x24C9;][1]

Creates a function that invokes the method at `object[key]` with `partials`
prepended to the arguments it receives.
<br>
<br>
This method differs from `_.bind` by allowing bound functions to reference
methods that may be redefined or don't yet exist. See
[Peter Michaux's article](http://peter.michaux.ca/articles/lazy-function-definition-pattern)
for more details.
<br>
<br>
The `_.bindKey.placeholder` value, which defaults to `_` in monolithic
builds, may be used as a placeholder for partially applied arguments.

#### 起始版本
0.10.0
#### 参数
1. `object` *(Object)*: The object to invoke the method on.
2. `key` *(string)*: The key of the method.
3. `[partials]` *(...&#42;)*: The arguments to be partially applied.

#### 返回结果
*(Function)*: Returns the new bound function.

####示例
```js
var object = {
  'user': 'fred',
  'greet': function(greeting, punctuation) {
    return greeting + ' ' + this.user + punctuation;
  }
};

var bound = _.bindKey(object, 'greet', 'hi');
bound('!');
// => 'hi fred!'

object.greet = function(greeting, punctuation) {
  return greeting + 'ya ' + this.user + punctuation;
};

bound('!');
// => 'hiya fred!'

// Bound with placeholders.
var bound = _.bindKey(object, 'greet', _, '!');
bound('hi');
// => 'hiya fred!'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_curryfunc-arityfunclength"><code>_.curry(func, [arity=func.length])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10062 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.curry "查看Npm包") [&#x24C9;][1]

Creates a function that accepts arguments of `func` and either invokes
`func` returning its result, if at least `arity` number of arguments have
been provided, or returns a function that accepts the remaining `func`
arguments, and so on. The arity of `func` may be specified if `func.length`
is not sufficient.
<br>
<br>
The `_.curry.placeholder` value, which defaults to `_` in monolithic builds,
may be used as a placeholder for provided arguments.
<br>
<br>
**提示:** This method doesn't set the "length" property of curried functions.

#### 起始版本
2.0.0
#### 参数
1. `func` *(Function)*: The function to curry.
2. `[arity=func.length]` *(number)*: The arity of `func`.

#### 返回结果
*(Function)*: Returns the new curried function.

####示例
```js
var abc = function(a, b, c) {
  return [a, b, c];
};

var curried = _.curry(abc);

curried(1)(2)(3);
// => [1, 2, 3]

curried(1, 2)(3);
// => [1, 2, 3]

curried(1, 2, 3);
// => [1, 2, 3]

// Curried with placeholders.
curried(1)(_, 3)(2);
// => [1, 2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_curryrightfunc-arityfunclength"><code>_.curryRight(func, [arity=func.length])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10107 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.curryright "查看Npm包") [&#x24C9;][1]

This method is like `_.curry` except that arguments are applied to `func`
in the manner of `_.partialRight` instead of `_.partial`.
<br>
<br>
The `_.curryRight.placeholder` value, which defaults to `_` in monolithic
builds, may be used as a placeholder for provided arguments.
<br>
<br>
**提示:** This method doesn't set the "length" property of curried functions.

#### 起始版本
3.0.0
#### 参数
1. `func` *(Function)*: The function to curry.
2. `[arity=func.length]` *(number)*: The arity of `func`.

#### 返回结果
*(Function)*: Returns the new curried function.

####示例
```js
var abc = function(a, b, c) {
  return [a, b, c];
};

var curried = _.curryRight(abc);

curried(3)(2)(1);
// => [1, 2, 3]

curried(2, 3)(1);
// => [1, 2, 3]

curried(1, 2, 3);
// => [1, 2, 3]

// Curried with placeholders.
curried(3)(1, _)(2);
// => [1, 2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_debouncefunc-wait0-options"><code>_.debounce(func, [wait=0], [options={}])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10168 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.debounce "查看Npm包") [&#x24C9;][1]

Creates a debounced function that delays invoking `func` until after `wait`
milliseconds have elapsed since the last time the debounced function was
invoked. The debounced function comes with a `cancel` method to cancel
delayed `func` invocations and a `flush` method to immediately invoke them.
Provide `options` to indicate whether `func` should be invoked on the
leading and/or trailing edge of the `wait` timeout. The `func` is invoked
with the last arguments provided to the debounced function. Subsequent
calls to the debounced function return the result of the last `func`
invocation.
<br>
<br>
**提示:** If `leading` and `trailing` options are `true`, `func` is
invoked on the trailing edge of the timeout only if the debounced function
is invoked more than once during the `wait` timeout.
<br>
<br>
If `wait` is `0` and `leading` is `false`, `func` invocation is deferred
until to the next tick, similar to `setTimeout` with a timeout of `0`.
<br>
<br>
See [David Corbacho's article](https://css-tricks.com/debouncing-throttling-explained-examples/)
for details over the differences between `_.debounce` and `_.throttle`.

#### 起始版本
0.1.0
#### 参数
1. `func` *(Function)*: The function to debounce.
2. `[wait=0]` *(number)*: The number of milliseconds to delay.
3. `[options={}]` *(Object)*: The options object.
4. `[options.leading=false]` *(boolean)*: Specify invoking on the leading edge of the timeout.
5. `[options.maxWait]` *(number)*: The maximum time `func` is allowed to be delayed before it's invoked.
6. `[options.trailing=true]` *(boolean)*: Specify invoking on the trailing edge of the timeout.

#### 返回结果
*(Function)*: Returns the new debounced function.

####示例
```js
// Avoid costly calculations while the window size is in flux.
jQuery(window).on('resize', _.debounce(calculateLayout, 150));

// Invoke `sendMail` when clicked, debouncing subsequent calls.
jQuery(element).on('click', _.debounce(sendMail, 300, {
  'leading': true,
  'trailing': false
}));

// Ensure `batchLog` is invoked once after 1 second of debounced calls.
var debounced = _.debounce(batchLog, 250, { 'maxWait': 1000 });
var source = new EventSource('/stream');
jQuery(source).on('message', debounced);

// Cancel the trailing debounced invocation.
jQuery(window).on('popstate', debounced.cancel);
```
---

<!-- /div -->

<!-- div -->

<h3 id="_deferfunc-args"><code>_.defer(func, [args])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10308 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.defer "查看Npm包") [&#x24C9;][1]

Defers invoking the `func` until the current call stack has cleared. Any
additional arguments are provided to `func` when it's invoked.

#### 起始版本
0.1.0
#### 参数
1. `func` *(Function)*: The function to defer.
2. `[args]` *(...&#42;)*: The arguments to invoke `func` with.

#### 返回结果
*(number)*: Returns the timer id.

####示例
```js
_.defer(function(text) {
  console.log(text);
}, 'deferred');
// => Logs 'deferred' after one millisecond.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_delayfunc-wait-args"><code>_.delay(func, wait, [args])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10331 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.delay "查看Npm包") [&#x24C9;][1]

Invokes `func` after `wait` milliseconds. Any additional arguments are
provided to `func` when it's invoked.

#### 起始版本
0.1.0
#### 参数
1. `func` *(Function)*: The function to delay.
2. `wait` *(number)*: The number of milliseconds to delay invocation.
3. `[args]` *(...&#42;)*: The arguments to invoke `func` with.

#### 返回结果
*(number)*: Returns the timer id.

####示例
```js
_.delay(function(text) {
  console.log(text);
}, 1000, 'later');
// => Logs 'later' after one second.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flipfunc"><code>_.flip(func)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10353 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flip "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with arguments reversed.

#### 起始版本
4.0.0
#### 参数
1. `func` *(Function)*: The function to flip arguments for.

#### 返回结果
*(Function)*: Returns the new flipped function.

####示例
```js
var flipped = _.flip(function() {
  return _.toArray(arguments);
});

flipped('a', 'b', 'c', 'd');
// => ['d', 'c', 'b', 'a']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_memoizefunc-resolver"><code>_.memoize(func, [resolver])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10401 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.memoize "查看Npm包") [&#x24C9;][1]

Creates a function that memoizes the result of `func`. If `resolver` is
provided, it determines the cache key for storing the result based on the
arguments provided to the memoized function. By default, the first argument
provided to the memoized function is used as the map cache key. The `func`
is invoked with the `this` binding of the memoized function.
<br>
<br>
**提示:** The cache is exposed as the `cache` property on the memoized
function. Its creation may be customized by replacing the `_.memoize.Cache`
constructor with one whose instances implement the
[`Map`](http://ecma-international.org/ecma-262/7.0/#sec-properties-of-the-map-prototype-object)
method interface of `delete`, `get`, `has`, and `set`.

#### 起始版本
0.1.0
#### 参数
1. `func` *(Function)*: The function to have its output memoized.
2. `[resolver]` *(Function)*: The function to resolve the cache key.

#### 返回结果
*(Function)*: Returns the new memoized function.

####示例
```js
var object = { 'a': 1, 'b': 2 };
var other = { 'c': 3, 'd': 4 };

var values = _.memoize(_.values);
values(object);
// => [1, 2]

values(other);
// => [3, 4]

object.a = 2;
values(object);
// => [1, 2]

// Modify the result cache.
values.cache.set(object, ['a', 'b']);
values(object);
// => ['a', 'b']

// Replace `_.memoize.Cache`.
_.memoize.Cache = WeakMap;
```
---

<!-- /div -->

<!-- div -->

<h3 id="_negatepredicate"><code>_.negate(predicate)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10444 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.negate "查看Npm包") [&#x24C9;][1]

Creates a function that negates the result of the predicate `func`. The
`func` predicate is invoked with the `this` binding and arguments of the
created function.

#### 起始版本
3.0.0
#### 参数
1. `predicate` *(Function)*: The predicate to negate.

#### 返回结果
*(Function)*: Returns the new negated function.

####示例
```js
function isEven(n) {
  return n % 2 == 0;
}

_.filter([1, 2, 3, 4, 5, 6], _.negate(isEven));
// => [1, 3, 5]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_oncefunc"><code>_.once(func)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10478 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.once "查看Npm包") [&#x24C9;][1]

Creates a function that is restricted to invoking `func` once. Repeat calls
to the function return the value of the first invocation. The `func` is
invoked with the `this` binding and arguments of the created function.

#### 起始版本
0.1.0
#### 参数
1. `func` *(Function)*: The function to restrict.

#### 返回结果
*(Function)*: Returns the new restricted function.

####示例
```js
var initialize = _.once(createApplication);
initialize();
initialize();
// => `createApplication` is invoked once
```
---

<!-- /div -->

<!-- div -->

<h3 id="_overargsfunc-transforms_identity"><code>_.overArgs(func, [transforms=[_.identity]])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10513 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.overargs "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with its arguments transformed.

#### 起始版本
4.0.0
#### 参数
1. `func` *(Function)*: The function to wrap.
2. `[transforms=[_.identity]]` *(...(Function|Function&#91;&#93;))*: The argument transforms.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
function doubled(n) {
  return n * 2;
}

function square(n) {
  return n * n;
}

var func = _.overArgs(function(x, y) {
  return [x, y];
}, [square, doubled]);

func(9, 3);
// => [81, 6]

func(10, 5);
// => [100, 10]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_partialfunc-partials"><code>_.partial(func, [partials])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10563 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.partial "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with `partials` prepended to the
arguments it receives. This method is like `_.bind` except it does **not**
alter the `this` binding.
<br>
<br>
The `_.partial.placeholder` value, which defaults to `_` in monolithic
builds, may be used as a placeholder for partially applied arguments.
<br>
<br>
**提示:** This method doesn't set the "length" property of partially
applied functions.

#### 起始版本
0.2.0
#### 参数
1. `func` *(Function)*: The function to partially apply arguments to.
2. `[partials]` *(...&#42;)*: The arguments to be partially applied.

#### 返回结果
*(Function)*: Returns the new partially applied function.

####示例
```js
function greet(greeting, name) {
  return greeting + ' ' + name;
}

var sayHelloTo = _.partial(greet, 'hello');
sayHelloTo('fred');
// => 'hello fred'

// Partially applied with placeholders.
var greetFred = _.partial(greet, _, 'fred');
greetFred('hi');
// => 'hi fred'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_partialrightfunc-partials"><code>_.partialRight(func, [partials])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10600 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.partialright "查看Npm包") [&#x24C9;][1]

This method is like `_.partial` except that partially applied arguments
are appended to the arguments it receives.
<br>
<br>
The `_.partialRight.placeholder` value, which defaults to `_` in monolithic
builds, may be used as a placeholder for partially applied arguments.
<br>
<br>
**提示:** This method doesn't set the "length" property of partially
applied functions.

#### 起始版本
1.0.0
#### 参数
1. `func` *(Function)*: The function to partially apply arguments to.
2. `[partials]` *(...&#42;)*: The arguments to be partially applied.

#### 返回结果
*(Function)*: Returns the new partially applied function.

####示例
```js
function greet(greeting, name) {
  return greeting + ' ' + name;
}

var greetFred = _.partialRight(greet, 'fred');
greetFred('hi');
// => 'hi fred'

// Partially applied with placeholders.
var sayHelloTo = _.partialRight(greet, 'hello', _);
sayHelloTo('fred');
// => 'hello fred'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_reargfunc-indexes"><code>_.rearg(func, indexes)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10627 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.rearg "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with arguments arranged according
to the specified `indexes` where the argument value at the first index is
provided as the first argument, the argument value at the second index is
provided as the second argument, and so on.

#### 起始版本
3.0.0
#### 参数
1. `func` *(Function)*: The function to rearrange arguments for.
2. `indexes` *(...(number|number&#91;&#93;))*: The arranged argument indexes.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
var rearged = _.rearg(function(a, b, c) {
  return [a, b, c];
}, [2, 0, 1]);

rearged('b', 'c', 'a')
// => ['a', 'b', 'c']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_restfunc-startfunclength-1"><code>_.rest(func, [start=func.length-1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10656 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.rest "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with the `this` binding of the
created function and arguments from `start` and beyond provided as
an array.
<br>
<br>
**提示:** This method is based on the
[rest parameter](https://mdn.io/rest_parameters).

#### 起始版本
4.0.0
#### 参数
1. `func` *(Function)*: The function to apply a rest parameter to.
2. `[start=func.length-1]` *(number)*: The start position of the rest parameter.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
var say = _.rest(function(what, names) {
  return what + ' ' + _.initial(names).join(', ') +
    (_.size(names) > 1 ? ', & ' : '') + _.last(names);
});

say('hello', 'fred', 'barney', 'pebbles');
// => 'hello fred, barney, & pebbles'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_spreadfunc-start0"><code>_.spread(func, [start=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10698 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.spread "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with the `this` binding of the
create function and an array of arguments much like
[`Function#apply`](http://www.ecma-international.org/ecma-262/7.0/#sec-function.prototype.apply).
<br>
<br>
**提示:** This method is based on the
[spread operator](https://mdn.io/spread_operator).

#### 起始版本
3.2.0
#### 参数
1. `func` *(Function)*: The function to spread arguments over.
2. `[start=0]` *(number)*: The start position of the spread.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
var say = _.spread(function(who, what) {
  return who + ' says ' + what;
});

say(['fred', 'hello']);
// => 'fred says hello'

var numbers = Promise.all([
  Promise.resolve(40),
  Promise.resolve(36)
]);

numbers.then(_.spread(function(x, y) {
  return x + y;
}));
// => a Promise of 76
```
---

<!-- /div -->

<!-- div -->

<h3 id="_throttlefunc-wait0-options"><code>_.throttle(func, [wait=0], [options={}])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10758 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.throttle "查看Npm包") [&#x24C9;][1]

Creates a throttled function that only invokes `func` at most once per
every `wait` milliseconds. The throttled function comes with a `cancel`
method to cancel delayed `func` invocations and a `flush` method to
immediately invoke them. Provide `options` to indicate whether `func`
should be invoked on the leading and/or trailing edge of the `wait`
timeout. The `func` is invoked with the last arguments provided to the
throttled function. Subsequent calls to the throttled function return the
result of the last `func` invocation.
<br>
<br>
**提示:** If `leading` and `trailing` options are `true`, `func` is
invoked on the trailing edge of the timeout only if the throttled function
is invoked more than once during the `wait` timeout.
<br>
<br>
If `wait` is `0` and `leading` is `false`, `func` invocation is deferred
until to the next tick, similar to `setTimeout` with a timeout of `0`.
<br>
<br>
See [David Corbacho's article](https://css-tricks.com/debouncing-throttling-explained-examples/)
for details over the differences between `_.throttle` and `_.debounce`.

#### 起始版本
0.1.0
#### 参数
1. `func` *(Function)*: The function to throttle.
2. `[wait=0]` *(number)*: The number of milliseconds to throttle invocations to.
3. `[options={}]` *(Object)*: The options object.
4. `[options.leading=true]` *(boolean)*: Specify invoking on the leading edge of the timeout.
5. `[options.trailing=true]` *(boolean)*: Specify invoking on the trailing edge of the timeout.

#### 返回结果
*(Function)*: Returns the new throttled function.

####示例
```js
// Avoid excessively updating the position while scrolling.
jQuery(window).on('scroll', _.throttle(updatePosition, 100));

// Invoke `renewToken` when the click event is fired, but not more than once every 5 minutes.
var throttled = _.throttle(renewToken, 300000, { 'trailing': false });
jQuery(element).on('click', throttled);

// Cancel the trailing throttled invocation.
jQuery(window).on('popstate', throttled.cancel);
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unaryfunc"><code>_.unary(func)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10791 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.unary "查看Npm包") [&#x24C9;][1]

Creates a function that accepts up to one argument, ignoring any
additional arguments.

#### 起始版本
4.0.0
#### 参数
1. `func` *(Function)*: The function to cap arguments for.

#### 返回结果
*(Function)*: Returns the new capped function.

####示例
```js
_.map(['6', '8', '10'], _.unary(parseInt));
// => [6, 8, 10]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_wrapvalue-wrapperidentity"><code>_.wrap(value, [wrapper=identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10817 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.wrap "查看Npm包") [&#x24C9;][1]

Creates a function that provides `value` to `wrapper` as its first
argument. Any additional arguments provided to the function are appended
to those provided to the `wrapper`. The wrapper is invoked with the `this`
binding of the created function.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to wrap.
2. `[wrapper=identity]` *(Function)*: The wrapper function.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
var p = _.wrap(_.escape, function(func, text) {
  return '<p>' + func(text) + '</p>';
});

p('fred, barney, & pebbles');
// => '<p>fred, barney, &amp; pebbles</p>'
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Lang” Methods`

<!-- div -->

<h3 id="_castarrayvalue"><code>_.castArray(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10857 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.castarray "查看Npm包") [&#x24C9;][1]

Casts `value` as an array if it's not one.

#### 起始版本
4.4.0
#### 参数
1. `value` *(&#42;)*: The value to inspect.

#### 返回结果
*(Array)*: Returns the cast array.

####示例
```js
_.castArray(1);
// => [1]

_.castArray({ 'a': 1 });
// => [{ 'a': 1 }]

_.castArray('abc');
// => ['abc']

_.castArray(null);
// => [null]

_.castArray(undefined);
// => [undefined]

_.castArray();
// => []

var array = [1, 2, 3];
console.log(_.castArray(array) === array);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_clonevalue"><code>_.clone(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10891 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.clone "查看Npm包") [&#x24C9;][1]

Creates a shallow clone of `value`.
<br>
<br>
**提示:** This method is loosely based on the
[structured clone algorithm](https://mdn.io/Structured_clone_algorithm)
and supports cloning arrays, array buffers, booleans, date objects, maps,
numbers, `Object` objects, regexes, sets, strings, symbols, and typed
arrays. The own enumerable properties of `arguments` objects are cloned
as plain objects. An empty object is returned for uncloneable values such
as error objects, functions, DOM nodes, and WeakMaps.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to clone.

#### 返回结果
*(&#42;)*: Returns the cloned value.

####示例
```js
var objects = [{ 'a': 1 }, { 'b': 2 }];

var shallow = _.clone(objects);
console.log(shallow[0] === objects[0]);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_clonedeepvalue"><code>_.cloneDeep(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10948 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.clonedeep "查看Npm包") [&#x24C9;][1]

This method is like `_.clone` except that it recursively clones `value`.

#### 起始版本
1.0.0
#### 参数
1. `value` *(&#42;)*: The value to recursively clone.

#### 返回结果
*(&#42;)*: Returns the deep cloned value.

####示例
```js
var objects = [{ 'a': 1 }, { 'b': 2 }];

var deep = _.cloneDeep(objects);
console.log(deep[0] === objects[0]);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_clonedeepwithvalue-customizer"><code>_.cloneDeepWith(value, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10980 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.clonedeepwith "查看Npm包") [&#x24C9;][1]

This method is like `_.cloneWith` except that it recursively clones `value`.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to recursively clone.
2. `[customizer]` *(Function)*: The function to customize cloning.

#### 返回结果
*(&#42;)*: Returns the deep cloned value.

####示例
```js
function customizer(value) {
  if (_.isElement(value)) {
    return value.cloneNode(true);
  }
}

var el = _.cloneDeepWith(document.body, customizer);

console.log(el === document.body);
// => false
console.log(el.nodeName);
// => 'BODY'
console.log(el.childNodes.length);
// => 20
```
---

<!-- /div -->

<!-- div -->

<h3 id="_clonewithvalue-customizer"><code>_.cloneWith(value, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L10926 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.clonewith "查看Npm包") [&#x24C9;][1]

This method is like `_.clone` except that it accepts `customizer` which
is invoked to produce the cloned value. If `customizer` returns `undefined`,
cloning is handled by the method instead. The `customizer` is invoked with
up to four arguments; *(value [, index|key, object, stack])*.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to clone.
2. `[customizer]` *(Function)*: The function to customize cloning.

#### 返回结果
*(&#42;)*: Returns the cloned value.

####示例
```js
function customizer(value) {
  if (_.isElement(value)) {
    return value.cloneNode(false);
  }
}

var el = _.cloneWith(document.body, customizer);

console.log(el === document.body);
// => false
console.log(el.nodeName);
// => 'BODY'
console.log(el.childNodes.length);
// => 0
```
---

<!-- /div -->

<!-- div -->

<h3 id="_conformstoobject-source"><code>_.conformsTo(object, source)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11008 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.conformsto "查看Npm包") [&#x24C9;][1]

Checks if `object` conforms to `source` by invoking the predicate
properties of `source` with the corresponding property values of `object`.
<br>
<br>
**提示:** This method is equivalent to `_.conforms` when `source` is
partially applied.

#### 起始版本
4.14.0
#### 参数
1. `object` *(Object)*: The object to inspect.
2. `source` *(Object)*: The object of property predicates to conform to.

#### 返回结果
*(boolean)*: Returns `true` if `object` conforms, else `false`.

####示例
```js
var object = { 'a': 1, 'b': 2 };

_.conformsTo(object, { 'b': function(n) { return n > 1; } });
// => true

_.conformsTo(object, { 'b': function(n) { return n > 2; } });
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_eqvalue-other"><code>_.eq(value, other)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11044 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.eq "查看Npm包") [&#x24C9;][1]

Performs a
[`SameValueZero`](http://ecma-international.org/ecma-262/7.0/#sec-samevaluezero)
comparison between two values to determine if they are equivalent.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to compare.
2. `other` *(&#42;)*: The other value to compare.

#### 返回结果
*(boolean)*: Returns `true` if the values are equivalent, else `false`.

####示例
```js
var object = { 'a': 1 };
var other = { 'a': 1 };

_.eq(object, object);
// => true

_.eq(object, other);
// => false

_.eq('a', 'a');
// => true

_.eq('a', Object('a'));
// => false

_.eq(NaN, NaN);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_gtvalue-other"><code>_.gt(value, other)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11071 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.gt "查看Npm包") [&#x24C9;][1]

Checks if `value` is greater than `other`.

#### 起始版本
3.9.0
#### 参数
1. `value` *(&#42;)*: The value to compare.
2. `other` *(&#42;)*: The other value to compare.

#### 返回结果
*(boolean)*: Returns `true` if `value` is greater than `other`, else `false`.

####示例
```js
_.gt(3, 1);
// => true

_.gt(3, 3);
// => false

_.gt(1, 3);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_gtevalue-other"><code>_.gte(value, other)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11096 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.gte "查看Npm包") [&#x24C9;][1]

Checks if `value` is greater than or equal to `other`.

#### 起始版本
3.9.0
#### 参数
1. `value` *(&#42;)*: The value to compare.
2. `other` *(&#42;)*: The other value to compare.

#### 返回结果
*(boolean)*: Returns `true` if `value` is greater than or equal to `other`, else `false`.

####示例
```js
_.gte(3, 1);
// => true

_.gte(3, 3);
// => true

_.gte(1, 3);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isargumentsvalue"><code>_.isArguments(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11118 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isarguments "查看Npm包") [&#x24C9;][1]

Checks if `value` is likely an `arguments` object.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is an `arguments` object, else `false`.

####示例
```js
_.isArguments(function() { return arguments; }());
// => true

_.isArguments([1, 2, 3]);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isarrayvalue"><code>_.isArray(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11147 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isarray "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as an `Array` object.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is an array, else `false`.

####示例
```js
_.isArray([1, 2, 3]);
// => true

_.isArray(document.body.children);
// => false

_.isArray('abc');
// => false

_.isArray(_.noop);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isarraybuffervalue"><code>_.isArrayBuffer(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11166 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isarraybuffer "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as an `ArrayBuffer` object.

#### 起始版本
4.3.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is an array buffer, else `false`.

####示例
```js
_.isArrayBuffer(new ArrayBuffer(2));
// => true

_.isArrayBuffer(new Array(2));
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isarraylikevalue"><code>_.isArrayLike(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11193 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isarraylike "查看Npm包") [&#x24C9;][1]

Checks if `value` is array-like. A value is considered array-like if it's
not a function and has a `value.length` that's an integer greater than or
equal to `0` and less than or equal to `Number.MAX_SAFE_INTEGER`.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is array-like, else `false`.

####示例
```js
_.isArrayLike([1, 2, 3]);
// => true

_.isArrayLike(document.body.children);
// => true

_.isArrayLike('abc');
// => true

_.isArrayLike(_.noop);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isarraylikeobjectvalue"><code>_.isArrayLikeObject(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11222 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isarraylikeobject "查看Npm包") [&#x24C9;][1]

This method is like `_.isArrayLike` except that it also checks if `value`
is an object.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is an array-like object, else `false`.

####示例
```js
_.isArrayLikeObject([1, 2, 3]);
// => true

_.isArrayLikeObject(document.body.children);
// => true

_.isArrayLikeObject('abc');
// => false

_.isArrayLikeObject(_.noop);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isbooleanvalue"><code>_.isBoolean(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11243 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isboolean "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a boolean primitive or object.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a boolean, else `false`.

####示例
```js
_.isBoolean(false);
// => true

_.isBoolean(null);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isbuffervalue"><code>_.isBuffer(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11265 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isbuffer "查看Npm包") [&#x24C9;][1]

Checks if `value` is a buffer.

#### 起始版本
4.3.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a buffer, else `false`.

####示例
```js
_.isBuffer(new Buffer(2));
// => true

_.isBuffer(new Uint8Array(2));
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isdatevalue"><code>_.isDate(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11284 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isdate "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `Date` object.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a date object, else `false`.

####示例
```js
_.isDate(new Date);
// => true

_.isDate('Mon April 23 2012');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_iselementvalue"><code>_.isElement(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11303 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.iselement "查看Npm包") [&#x24C9;][1]

Checks if `value` is likely a DOM element.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a DOM element, else `false`.

####示例
```js
_.isElement(document.body);
// => true

_.isElement('<body>');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isemptyvalue"><code>_.isEmpty(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11340 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isempty "查看Npm包") [&#x24C9;][1]

Checks if `value` is an empty object, collection, map, or set.
<br>
<br>
Objects are considered empty if they have no own enumerable string keyed
properties.
<br>
<br>
Array-like values such as `arguments` objects, arrays, buffers, strings, or
jQuery-like collections are considered empty if they have a `length` of `0`.
Similarly, maps and sets are considered empty if they have a `size` of `0`.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is empty, else `false`.

####示例
```js
_.isEmpty(null);
// => true

_.isEmpty(true);
// => true

_.isEmpty(1);
// => true

_.isEmpty([1, 2, 3]);
// => false

_.isEmpty({ 'a': 1 });
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isequalvalue-other"><code>_.isEqual(value, other)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11389 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isequal "查看Npm包") [&#x24C9;][1]

Performs a deep comparison between two values to determine if they are
equivalent.
<br>
<br>
**提示:** This method supports comparing arrays, array buffers, booleans,
date objects, error objects, maps, numbers, `Object` objects, regexes,
sets, strings, symbols, and typed arrays. `Object` objects are compared
by their own, not inherited, enumerable properties. Functions and DOM
nodes are **not** supported.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to compare.
2. `other` *(&#42;)*: The other value to compare.

#### 返回结果
*(boolean)*: Returns `true` if the values are equivalent, else `false`.

####示例
```js
var object = { 'a': 1 };
var other = { 'a': 1 };

_.isEqual(object, other);
// => true

object === other;
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isequalwithvalue-other-customizer"><code>_.isEqualWith(value, other, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11425 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isequalwith "查看Npm包") [&#x24C9;][1]

This method is like `_.isEqual` except that it accepts `customizer` which
is invoked to compare values. If `customizer` returns `undefined`, comparisons
are handled by the method instead. The `customizer` is invoked with up to
six arguments: *(objValue, othValue [, index|key, object, other, stack])*.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to compare.
2. `other` *(&#42;)*: The other value to compare.
3. `[customizer]` *(Function)*: The function to customize comparisons.

#### 返回结果
*(boolean)*: Returns `true` if the values are equivalent, else `false`.

####示例
```js
function isGreeting(value) {
  return /^h(?:i|ello)$/.test(value);
}

function customizer(objValue, othValue) {
  if (isGreeting(objValue) && isGreeting(othValue)) {
    return true;
  }
}

var array = ['hello', 'goodbye'];
var other = ['hi', 'goodbye'];

_.isEqualWith(array, other, customizer);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_iserrorvalue"><code>_.isError(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11449 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.iserror "查看Npm包") [&#x24C9;][1]

Checks if `value` is an `Error`, `EvalError`, `RangeError`, `ReferenceError`,
`SyntaxError`, `TypeError`, or `URIError` object.

#### 起始版本
3.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is an error object, else `false`.

####示例
```js
_.isError(new Error);
// => true

_.isError(Error);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isfinitevalue"><code>_.isFinite(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11483 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isfinite "查看Npm包") [&#x24C9;][1]

Checks if `value` is a finite primitive number.
<br>
<br>
**提示:** This method is based on
[`Number.isFinite`](https://mdn.io/Number/isFinite).

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a finite number, else `false`.

####示例
```js
_.isFinite(3);
// => true

_.isFinite(Number.MIN_VALUE);
// => true

_.isFinite(Infinity);
// => false

_.isFinite('3');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isfunctionvalue"><code>_.isFunction(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11504 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isfunction "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `Function` object.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a function, else `false`.

####示例
```js
_.isFunction(_);
// => true

_.isFunction(/abc/);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isintegervalue"><code>_.isInteger(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11537 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isinteger "查看Npm包") [&#x24C9;][1]

Checks if `value` is an integer.
<br>
<br>
**提示:** This method is based on
[`Number.isInteger`](https://mdn.io/Number/isInteger).

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is an integer, else `false`.

####示例
```js
_.isInteger(3);
// => true

_.isInteger(Number.MIN_VALUE);
// => false

_.isInteger(Infinity);
// => false

_.isInteger('3');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_islengthvalue"><code>_.isLength(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11567 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.islength "查看Npm包") [&#x24C9;][1]

Checks if `value` is a valid array-like length.
<br>
<br>
**提示:** This method is loosely based on
[`ToLength`](http://ecma-international.org/ecma-262/7.0/#sec-tolength).

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a valid length, else `false`.

####示例
```js
_.isLength(3);
// => true

_.isLength(Number.MIN_VALUE);
// => false

_.isLength(Infinity);
// => false

_.isLength('3');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ismapvalue"><code>_.isMap(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11647 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.ismap "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `Map` object.

#### 起始版本
4.3.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a map, else `false`.

####示例
```js
_.isMap(new Map);
// => true

_.isMap(new WeakMap);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ismatchobject-source"><code>_.isMatch(object, source)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11677 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.ismatch "查看Npm包") [&#x24C9;][1]

Performs a partial deep comparison between `object` and `source` to
determine if `object` contains equivalent property values.
<br>
<br>
**提示:** This method is equivalent to `_.matches` when `source` is
partially applied.
<br>
<br>
Partial comparisons will match empty array and empty object `source`
values against any array or object value, respectively. See `_.isEqual`
for a list of supported value comparisons.

#### 起始版本
3.0.0
#### 参数
1. `object` *(Object)*: The object to inspect.
2. `source` *(Object)*: The object of property values to match.

#### 返回结果
*(boolean)*: Returns `true` if `object` is a match, else `false`.

####示例
```js
var object = { 'a': 1, 'b': 2 };

_.isMatch(object, { 'b': 2 });
// => true

_.isMatch(object, { 'b': 1 });
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ismatchwithobject-source-customizer"><code>_.isMatchWith(object, source, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11713 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.ismatchwith "查看Npm包") [&#x24C9;][1]

This method is like `_.isMatch` except that it accepts `customizer` which
is invoked to compare values. If `customizer` returns `undefined`, comparisons
are handled by the method instead. The `customizer` is invoked with five
arguments: *(objValue, srcValue, index|key, object, source)*.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The object to inspect.
2. `source` *(Object)*: The object of property values to match.
3. `[customizer]` *(Function)*: The function to customize comparisons.

#### 返回结果
*(boolean)*: Returns `true` if `object` is a match, else `false`.

####示例
```js
function isGreeting(value) {
  return /^h(?:i|ello)$/.test(value);
}

function customizer(objValue, srcValue) {
  if (isGreeting(objValue) && isGreeting(srcValue)) {
    return true;
  }
}

var object = { 'greeting': 'hello' };
var source = { 'greeting': 'hi' };

_.isMatchWith(object, source, customizer);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isnanvalue"><code>_.isNaN(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11746 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isnan "查看Npm包") [&#x24C9;][1]

Checks if `value` is `NaN`.
<br>
<br>
**提示:** This method is based on
[`Number.isNaN`](https://mdn.io/Number/isNaN) and is not the same as
global [`isNaN`](https://mdn.io/isNaN) which returns `true` for
`undefined` and other non-number values.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is `NaN`, else `false`.

####示例
```js
_.isNaN(NaN);
// => true

_.isNaN(new Number(NaN));
// => true

isNaN(undefined);
// => true

_.isNaN(undefined);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isnativevalue"><code>_.isNative(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11779 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isnative "查看Npm包") [&#x24C9;][1]

Checks if `value` is a pristine native function.
<br>
<br>
**提示:** This method can't reliably detect native functions in the presence
of the core-js package because core-js circumvents this kind of detection.
Despite multiple requests, the core-js maintainer has made it clear: any
attempt to fix the detection will be obstructed. As a result, we're left
with little choice but to throw an error. Unfortunately, this also affects
packages, like [babel-polyfill](https://www.npmjs.com/package/babel-polyfill),
which rely on core-js.

#### 起始版本
3.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a native function, else `false`.

####示例
```js
_.isNative(Array.prototype.push);
// => true

_.isNative(_);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isnilvalue"><code>_.isNil(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11827 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isnil "查看Npm包") [&#x24C9;][1]

Checks if `value` is `null` or `undefined`.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is nullish, else `false`.

####示例
```js
_.isNil(null);
// => true

_.isNil(void 0);
// => true

_.isNil(NaN);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isnullvalue"><code>_.isNull(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11803 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isnull "查看Npm包") [&#x24C9;][1]

Checks if `value` is `null`.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is `null`, else `false`.

####示例
```js
_.isNull(null);
// => true

_.isNull(void 0);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isnumbervalue"><code>_.isNumber(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11857 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isnumber "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `Number` primitive or object.
<br>
<br>
**提示:** To exclude `Infinity`, `-Infinity`, and `NaN`, which are
classified as numbers, use the `_.isFinite` method.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a number, else `false`.

####示例
```js
_.isNumber(3);
// => true

_.isNumber(Number.MIN_VALUE);
// => true

_.isNumber(Infinity);
// => true

_.isNumber('3');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isobjectvalue"><code>_.isObject(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11597 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isobject "查看Npm包") [&#x24C9;][1]

Checks if `value` is the
[language type](http://www.ecma-international.org/ecma-262/7.0/#sec-ecmascript-language-types)
of `Object`. *(e.g. arrays, functions, objects, regexes, `new Number(0)`, and `new String('')`)*

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is an object, else `false`.

####示例
```js
_.isObject({});
// => true

_.isObject([1, 2, 3]);
// => true

_.isObject(_.noop);
// => true

_.isObject(null);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isobjectlikevalue"><code>_.isObjectLike(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11626 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isobjectlike "查看Npm包") [&#x24C9;][1]

Checks if `value` is object-like. A value is object-like if it's not `null`
and has a `typeof` result of "object".

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is object-like, else `false`.

####示例
```js
_.isObjectLike({});
// => true

_.isObjectLike([1, 2, 3]);
// => true

_.isObjectLike(_.noop);
// => false

_.isObjectLike(null);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isplainobjectvalue"><code>_.isPlainObject(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11890 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isplainobject "查看Npm包") [&#x24C9;][1]

Checks if `value` is a plain object, that is, an object created by the
`Object` constructor or one with a `[[Prototype]]` of `null`.

#### 起始版本
0.8.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a plain object, else `false`.

####示例
```js
function Foo() {
  this.a = 1;
}

_.isPlainObject(new Foo);
// => false

_.isPlainObject([1, 2, 3]);
// => false

_.isPlainObject({ 'x': 0, 'y': 0 });
// => true

_.isPlainObject(Object.create(null));
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isregexpvalue"><code>_.isRegExp(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11920 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isregexp "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `RegExp` object.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a regexp, else `false`.

####示例
```js
_.isRegExp(/abc/);
// => true

_.isRegExp('/abc/');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_issafeintegervalue"><code>_.isSafeInteger(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11949 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.issafeinteger "查看Npm包") [&#x24C9;][1]

Checks if `value` is a safe integer. An integer is safe if it's an IEEE-754
double precision number which isn't the result of a rounded unsafe integer.
<br>
<br>
**提示:** This method is based on
[`Number.isSafeInteger`](https://mdn.io/Number/isSafeInteger).

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a safe integer, else `false`.

####示例
```js
_.isSafeInteger(3);
// => true

_.isSafeInteger(Number.MIN_VALUE);
// => false

_.isSafeInteger(Infinity);
// => false

_.isSafeInteger('3');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_issetvalue"><code>_.isSet(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11970 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isset "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `Set` object.

#### 起始版本
4.3.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a set, else `false`.

####示例
```js
_.isSet(new Set);
// => true

_.isSet(new WeakSet);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isstringvalue"><code>_.isString(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L11989 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isstring "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `String` primitive or object.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a string, else `false`.

####示例
```js
_.isString('abc');
// => true

_.isString(1);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_issymbolvalue"><code>_.isSymbol(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12011 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.issymbol "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `Symbol` primitive or object.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a symbol, else `false`.

####示例
```js
_.isSymbol(Symbol.iterator);
// => true

_.isSymbol('abc');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_istypedarrayvalue"><code>_.isTypedArray(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12033 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.istypedarray "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a typed array.

#### 起始版本
3.0.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a typed array, else `false`.

####示例
```js
_.isTypedArray(new Uint8Array);
// => true

_.isTypedArray([]);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isundefinedvalue"><code>_.isUndefined(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12052 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isundefined "查看Npm包") [&#x24C9;][1]

Checks if `value` is `undefined`.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is `undefined`, else `false`.

####示例
```js
_.isUndefined(void 0);
// => true

_.isUndefined(null);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isweakmapvalue"><code>_.isWeakMap(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12073 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isweakmap "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `WeakMap` object.

#### 起始版本
4.3.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a weak map, else `false`.

####示例
```js
_.isWeakMap(new WeakMap);
// => true

_.isWeakMap(new Map);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_isweaksetvalue"><code>_.isWeakSet(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12094 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.isweakset "查看Npm包") [&#x24C9;][1]

Checks if `value` is classified as a `WeakSet` object.

#### 起始版本
4.3.0
#### 参数
1. `value` *(&#42;)*: The value to check.

#### 返回结果
*(boolean)*: Returns `true` if `value` is a weak set, else `false`.

####示例
```js
_.isWeakSet(new WeakSet);
// => true

_.isWeakSet(new Set);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ltvalue-other"><code>_.lt(value, other)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12121 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.lt "查看Npm包") [&#x24C9;][1]

Checks if `value` is less than `other`.

#### 起始版本
3.9.0
#### 参数
1. `value` *(&#42;)*: The value to compare.
2. `other` *(&#42;)*: The other value to compare.

#### 返回结果
*(boolean)*: Returns `true` if `value` is less than `other`, else `false`.

####示例
```js
_.lt(1, 3);
// => true

_.lt(3, 3);
// => false

_.lt(3, 1);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ltevalue-other"><code>_.lte(value, other)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12146 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.lte "查看Npm包") [&#x24C9;][1]

Checks if `value` is less than or equal to `other`.

#### 起始版本
3.9.0
#### 参数
1. `value` *(&#42;)*: The value to compare.
2. `other` *(&#42;)*: The other value to compare.

#### 返回结果
*(boolean)*: Returns `true` if `value` is less than or equal to `other`, else `false`.

####示例
```js
_.lte(1, 3);
// => true

_.lte(3, 3);
// => true

_.lte(3, 1);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_toarrayvalue"><code>_.toArray(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12173 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.toarray "查看Npm包") [&#x24C9;][1]

Converts `value` to an array.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to convert.

#### 返回结果
*(Array)*: Returns the converted array.

####示例
```js
_.toArray({ 'a': 1, 'b': 2 });
// => [1, 2]

_.toArray('abc');
// => ['a', 'b', 'c']

_.toArray(1);
// => []

_.toArray(null);
// => []
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tofinitevalue"><code>_.toFinite(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12212 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tofinite "查看Npm包") [&#x24C9;][1]

Converts `value` to a finite number.

#### 起始版本
4.12.0
#### 参数
1. `value` *(&#42;)*: The value to convert.

#### 返回结果
*(number)*: Returns the converted number.

####示例
```js
_.toFinite(3.2);
// => 3.2

_.toFinite(Number.MIN_VALUE);
// => 5e-324

_.toFinite(Infinity);
// => 1.7976931348623157e+308

_.toFinite('3.2');
// => 3.2
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tointegervalue"><code>_.toInteger(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12250 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tointeger "查看Npm包") [&#x24C9;][1]

Converts `value` to an integer.
<br>
<br>
**提示:** This method is loosely based on
[`ToInteger`](http://www.ecma-international.org/ecma-262/7.0/#sec-tointeger).

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to convert.

#### 返回结果
*(number)*: Returns the converted integer.

####示例
```js
_.toInteger(3.2);
// => 3

_.toInteger(Number.MIN_VALUE);
// => 0

_.toInteger(Infinity);
// => 1.7976931348623157e+308

_.toInteger('3.2');
// => 3
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tolengthvalue"><code>_.toLength(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12284 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tolength "查看Npm包") [&#x24C9;][1]

Converts `value` to an integer suitable for use as the length of an
array-like object.
<br>
<br>
**提示:** This method is based on
[`ToLength`](http://ecma-international.org/ecma-262/7.0/#sec-tolength).

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to convert.

#### 返回结果
*(number)*: Returns the converted integer.

####示例
```js
_.toLength(3.2);
// => 3

_.toLength(Number.MIN_VALUE);
// => 0

_.toLength(Infinity);
// => 4294967295

_.toLength('3.2');
// => 3
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tonumbervalue"><code>_.toNumber(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12311 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tonumber "查看Npm包") [&#x24C9;][1]

Converts `value` to a number.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to process.

#### 返回结果
*(number)*: Returns the number.

####示例
```js
_.toNumber(3.2);
// => 3.2

_.toNumber(Number.MIN_VALUE);
// => 5e-324

_.toNumber(Infinity);
// => Infinity

_.toNumber('3.2');
// => 3.2
```
---

<!-- /div -->

<!-- div -->

<h3 id="_toplainobjectvalue"><code>_.toPlainObject(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12356 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.toplainobject "查看Npm包") [&#x24C9;][1]

Converts `value` to a plain object flattening inherited enumerable string
keyed properties of `value` to own properties of the plain object.

#### 起始版本
3.0.0
#### 参数
1. `value` *(&#42;)*: The value to convert.

#### 返回结果
*(Object)*: Returns the converted plain object.

####示例
```js
function Foo() {
  this.b = 2;
}

Foo.prototype.c = 3;

_.assign({ 'a': 1 }, new Foo);
// => { 'a': 1, 'b': 2 }

_.assign({ 'a': 1 }, _.toPlainObject(new Foo));
// => { 'a': 1, 'b': 2, 'c': 3 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tosafeintegervalue"><code>_.toSafeInteger(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12384 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tosafeinteger "查看Npm包") [&#x24C9;][1]

Converts `value` to a safe integer. A safe integer can be compared and
represented correctly.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to convert.

#### 返回结果
*(number)*: Returns the converted integer.

####示例
```js
_.toSafeInteger(3.2);
// => 3

_.toSafeInteger(Number.MIN_VALUE);
// => 0

_.toSafeInteger(Infinity);
// => 9007199254740991

_.toSafeInteger('3.2');
// => 3
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tostringvalue"><code>_.toString(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12409 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tostring "查看Npm包") [&#x24C9;][1]

Converts `value` to a string. An empty string is returned for `null`
and `undefined` values. The sign of `-0` is preserved.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to process.

#### 返回结果
*(string)*: Returns the string.

####示例
```js
_.toString(null);
// => ''

_.toString(-0);
// => '-0'

_.toString([1, 2, 3]);
// => '1,2,3'
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Math” Methods`

<!-- div -->

<h3 id="_addaugend-addend"><code>_.add(augend, addend)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15975 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.add "查看Npm包") [&#x24C9;][1]

Adds two numbers.

#### 起始版本
3.4.0
#### 参数
1. `augend` *(number)*: The first number in an addition.
2. `addend` *(number)*: The second number in an addition.

#### 返回结果
*(number)*: Returns the total.

####示例
```js
_.add(6, 4);
// => 10
```
---

<!-- /div -->

<!-- div -->

<h3 id="_ceilnumber-precision0"><code>_.ceil(number, [precision=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16000 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.ceil "查看Npm包") [&#x24C9;][1]

Computes `number` rounded up to `precision`.

#### 起始版本
3.10.0
#### 参数
1. `number` *(number)*: The number to round up.
2. `[precision=0]` *(number)*: The precision to round up to.

#### 返回结果
*(number)*: Returns the rounded up number.

####示例
```js
_.ceil(4.006);
// => 5

_.ceil(6.004, 2);
// => 6.01

_.ceil(6040, -2);
// => 6100
```
---

<!-- /div -->

<!-- div -->

<h3 id="_dividedividend-divisor"><code>_.divide(dividend, divisor)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16017 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.divide "查看Npm包") [&#x24C9;][1]

Divide two numbers.

#### 起始版本
4.7.0
#### 参数
1. `dividend` *(number)*: The first number in a division.
2. `divisor` *(number)*: The second number in a division.

#### 返回结果
*(number)*: Returns the quotient.

####示例
```js
_.divide(6, 4);
// => 1.5
```
---

<!-- /div -->

<!-- div -->

<h3 id="_floornumber-precision0"><code>_.floor(number, [precision=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16042 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.floor "查看Npm包") [&#x24C9;][1]

Computes `number` rounded down to `precision`.

#### 起始版本
3.10.0
#### 参数
1. `number` *(number)*: The number to round down.
2. `[precision=0]` *(number)*: The precision to round down to.

#### 返回结果
*(number)*: Returns the rounded down number.

####示例
```js
_.floor(4.006);
// => 4

_.floor(0.046, 2);
// => 0.04

_.floor(4060, -2);
// => 4000
```
---

<!-- /div -->

<!-- div -->

<h3 id="_maxarray"><code>_.max(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16062 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.max "查看Npm包") [&#x24C9;][1]

Computes the maximum value of `array`. If `array` is empty or falsey,
`undefined` is returned.

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: The array to iterate over.

#### 返回结果
*(&#42;)*: Returns the maximum value.

####示例
```js
_.max([4, 2, 8, 6]);
// => 8

_.max([]);
// => undefined
```
---

<!-- /div -->

<!-- div -->

<h3 id="_maxbyarray-iteratee_identity"><code>_.maxBy(array, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16091 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.maxby "查看Npm包") [&#x24C9;][1]

This method is like `_.max` except that it accepts `iteratee` which is
invoked for each element in `array` to generate the criterion by which
the value is ranked. The iteratee is invoked with one argument: *(value)*.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(&#42;)*: Returns the maximum value.

####示例
```js
var objects = [{ 'n': 1 }, { 'n': 2 }];

_.maxBy(objects, function(o) { return o.n; });
// => { 'n': 2 }

// The `_.property` 的缩写
_.maxBy(objects, 'n');
// => { 'n': 2 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_meanarray"><code>_.mean(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16111 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.mean "查看Npm包") [&#x24C9;][1]

Computes the mean of the values in `array`.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to iterate over.

#### 返回结果
*(number)*: Returns the mean.

####示例
```js
_.mean([4, 2, 8, 6]);
// => 5
```
---

<!-- /div -->

<!-- div -->

<h3 id="_meanbyarray-iteratee_identity"><code>_.meanBy(array, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16138 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.meanby "查看Npm包") [&#x24C9;][1]

This method is like `_.mean` except that it accepts `iteratee` which is
invoked for each element in `array` to generate the value to be averaged.
The iteratee is invoked with one argument: *(value)*.

#### 起始版本
4.7.0
#### 参数
1. `array` *(Array)*: The array to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(number)*: Returns the mean.

####示例
```js
var objects = [{ 'n': 4 }, { 'n': 2 }, { 'n': 8 }, { 'n': 6 }];

_.meanBy(objects, function(o) { return o.n; });
// => 5

// The `_.property` 的缩写
_.meanBy(objects, 'n');
// => 5
```
---

<!-- /div -->

<!-- div -->

<h3 id="_minarray"><code>_.min(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16160 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.min "查看Npm包") [&#x24C9;][1]

Computes the minimum value of `array`. If `array` is empty or falsey,
`undefined` is returned.

#### 起始版本
0.1.0
#### 参数
1. `array` *(Array)*: The array to iterate over.

#### 返回结果
*(&#42;)*: Returns the minimum value.

####示例
```js
_.min([4, 2, 8, 6]);
// => 2

_.min([]);
// => undefined
```
---

<!-- /div -->

<!-- div -->

<h3 id="_minbyarray-iteratee_identity"><code>_.minBy(array, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16189 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.minby "查看Npm包") [&#x24C9;][1]

This method is like `_.min` except that it accepts `iteratee` which is
invoked for each element in `array` to generate the criterion by which
the value is ranked. The iteratee is invoked with one argument: *(value)*.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(&#42;)*: Returns the minimum value.

####示例
```js
var objects = [{ 'n': 1 }, { 'n': 2 }];

_.minBy(objects, function(o) { return o.n; });
// => { 'n': 1 }

// The `_.property` 的缩写
_.minBy(objects, 'n');
// => { 'n': 1 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_multiplymultiplier-multiplicand"><code>_.multiply(multiplier, multiplicand)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16210 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.multiply "查看Npm包") [&#x24C9;][1]

Multiply two numbers.

#### 起始版本
4.7.0
#### 参数
1. `multiplier` *(number)*: The first number in a multiplication.
2. `multiplicand` *(number)*: The second number in a multiplication.

#### 返回结果
*(number)*: Returns the product.

####示例
```js
_.multiply(6, 4);
// => 24
```
---

<!-- /div -->

<!-- div -->

<h3 id="_roundnumber-precision0"><code>_.round(number, [precision=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16235 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.round "查看Npm包") [&#x24C9;][1]

Computes `number` rounded to `precision`.

#### 起始版本
3.10.0
#### 参数
1. `number` *(number)*: The number to round.
2. `[precision=0]` *(number)*: The precision to round to.

#### 返回结果
*(number)*: Returns the rounded number.

####示例
```js
_.round(4.006);
// => 4

_.round(4.006, 2);
// => 4.01

_.round(4060, -2);
// => 4100
```
---

<!-- /div -->

<!-- div -->

<h3 id="_subtractminuend-subtrahend"><code>_.subtract(minuend, subtrahend)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16252 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.subtract "查看Npm包") [&#x24C9;][1]

Subtract two numbers.

#### 起始版本
4.0.0
#### 参数
1. `minuend` *(number)*: The first number in a subtraction.
2. `subtrahend` *(number)*: The second number in a subtraction.

#### 返回结果
*(number)*: Returns the difference.

####示例
```js
_.subtract(6, 4);
// => 2
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sumarray"><code>_.sum(array)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16270 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sum "查看Npm包") [&#x24C9;][1]

Computes the sum of the values in `array`.

#### 起始版本
3.4.0
#### 参数
1. `array` *(Array)*: The array to iterate over.

#### 返回结果
*(number)*: Returns the sum.

####示例
```js
_.sum([4, 2, 8, 6]);
// => 20
```
---

<!-- /div -->

<!-- div -->

<h3 id="_sumbyarray-iteratee_identity"><code>_.sumBy(array, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16299 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.sumby "查看Npm包") [&#x24C9;][1]

This method is like `_.sum` except that it accepts `iteratee` which is
invoked for each element in `array` to generate the value to be summed.
The iteratee is invoked with one argument: *(value)*.

#### 起始版本
4.0.0
#### 参数
1. `array` *(Array)*: The array to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(number)*: Returns the sum.

####示例
```js
var objects = [{ 'n': 4 }, { 'n': 2 }, { 'n': 8 }, { 'n': 6 }];

_.sumBy(objects, function(o) { return o.n; });
// => 20

// The `_.property` 的缩写
_.sumBy(objects, 'n');
// => 20
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Number” Methods`

<!-- div -->

<h3 id="_clampnumber-lower-upper"><code>_.clamp(number, [lower], upper)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13772 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.clamp "查看Npm包") [&#x24C9;][1]

Clamps `number` within the inclusive `lower` and `upper` bounds.

#### 起始版本
4.0.0
#### 参数
1. `number` *(number)*: The number to clamp.
2. `[lower]` *(number)*: The lower bound.
3. `upper` *(number)*: The upper bound.

#### 返回结果
*(number)*: Returns the clamped number.

####示例
```js
_.clamp(-10, -5, 5);
// => -5

_.clamp(10, -5, 5);
// => 5
```
---

<!-- /div -->

<!-- div -->

<h3 id="_inrangenumber-start0-end"><code>_.inRange(number, [start=0], end)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13826 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.inrange "查看Npm包") [&#x24C9;][1]

Checks if `n` is between `start` and up to, but not including, `end`. If
`end` is not specified, it's set to `start` with `start` then set to `0`.
If `start` is greater than `end` the params are swapped to support
negative ranges.

#### 起始版本
3.3.0
#### 参数
1. `number` *(number)*: The number to check.
2. `[start=0]` *(number)*: The start of the range.
3. `end` *(number)*: The end of the range.

#### 返回结果
*(boolean)*: Returns `true` if `number` is in the range, else `false`.

####示例
```js
_.inRange(3, 2, 4);
// => true

_.inRange(4, 8);
// => true

_.inRange(4, 2);
// => false

_.inRange(2, 2);
// => false

_.inRange(1.2, 2);
// => true

_.inRange(5.2, 4);
// => false

_.inRange(-3, -2, -6);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_randomlower0-upper1-floating"><code>_.random([lower=0], [upper=1], [floating])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13869 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.random "查看Npm包") [&#x24C9;][1]

Produces a random number between the inclusive `lower` and `upper` bounds.
If only one argument is provided a number between `0` and the given number
is returned. If `floating` is `true`, or either `lower` or `upper` are
floats, a floating-point number is returned instead of an integer.
<br>
<br>
**提示:** JavaScript follows the IEEE-754 standard for resolving
floating-point values which can produce unexpected results.

#### 起始版本
0.7.0
#### 参数
1. `[lower=0]` *(number)*: The lower bound.
2. `[upper=1]` *(number)*: The upper bound.
3. `[floating]` *(boolean)*: Specify returning a floating-point number.

#### 返回结果
*(number)*: Returns the random number.

####示例
```js
_.random(0, 5);
// => an integer between 0 and 5

_.random(5);
// => also an integer between 0 and 5

_.random(5, true);
// => a floating-point number between 0 and 5

_.random(1.2, 5.2);
// => a floating-point number between 1.2 and 5.2
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Object” Methods`

<!-- div -->

<h3 id="_assignobject-sources"><code>_.assign(object, [sources])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12447 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.assign "查看Npm包") [&#x24C9;][1]

Assigns own enumerable string keyed properties of source objects to the
destination object. Source objects are applied from left to right.
Subsequent sources overwrite property assignments of previous sources.
<br>
<br>
**提示:** This method mutates `object` and is loosely based on
[`Object.assign`](https://mdn.io/Object/assign).

#### 起始版本
0.10.0
#### 参数
1. `object` *(Object)*: The destination object.
2. `[sources]` *(...Object)*: The source objects.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function Foo() {
  this.a = 1;
}

function Bar() {
  this.c = 3;
}

Foo.prototype.b = 2;
Bar.prototype.d = 4;

_.assign({ 'a': 0 }, new Foo, new Bar);
// => { 'a': 1, 'c': 3 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_assigninobject-sources"><code>_.assignIn(object, [sources])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12490 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.assignin "查看Npm包") [&#x24C9;][1]

This method is like `_.assign` except that it iterates over own and
inherited source properties.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.0.0
#### Aliases
*_.extend*

#### 参数
1. `object` *(Object)*: The destination object.
2. `[sources]` *(...Object)*: The source objects.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function Foo() {
  this.a = 1;
}

function Bar() {
  this.c = 3;
}

Foo.prototype.b = 2;
Bar.prototype.d = 4;

_.assignIn({ 'a': 0 }, new Foo, new Bar);
// => { 'a': 1, 'b': 2, 'c': 3, 'd': 4 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_assigninwithobject-sources-customizer"><code>_.assignInWith(object, sources, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12523 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.assigninwith "查看Npm包") [&#x24C9;][1]

This method is like `_.assignIn` except that it accepts `customizer`
which is invoked to produce the assigned values. If `customizer` returns
`undefined`, assignment is handled by the method instead. The `customizer`
is invoked with five arguments: *(objValue, srcValue, key, object, source)*.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.0.0
#### Aliases
*_.extendWith*

#### 参数
1. `object` *(Object)*: The destination object.
2. `sources` *(...Object)*: The source objects.
3. `[customizer]` *(Function)*: The function to customize assigned values.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function customizer(objValue, srcValue) {
  return _.isUndefined(objValue) ? srcValue : objValue;
}

var defaults = _.partialRight(_.assignInWith, customizer);

defaults({ 'a': 1 }, { 'b': 2 }, { 'a': 3 });
// => { 'a': 1, 'b': 2 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_assignwithobject-sources-customizer"><code>_.assignWith(object, sources, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12555 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.assignwith "查看Npm包") [&#x24C9;][1]

This method is like `_.assign` except that it accepts `customizer`
which is invoked to produce the assigned values. If `customizer` returns
`undefined`, assignment is handled by the method instead. The `customizer`
is invoked with five arguments: *(objValue, srcValue, key, object, source)*.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The destination object.
2. `sources` *(...Object)*: The source objects.
3. `[customizer]` *(Function)*: The function to customize assigned values.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function customizer(objValue, srcValue) {
  return _.isUndefined(objValue) ? srcValue : objValue;
}

var defaults = _.partialRight(_.assignWith, customizer);

defaults({ 'a': 1 }, { 'b': 2 }, { 'a': 3 });
// => { 'a': 1, 'b': 2 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_atobject-paths"><code>_.at(object, [paths])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12576 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.at "查看Npm包") [&#x24C9;][1]

Creates an array of values corresponding to `paths` of `object`.

#### 起始版本
1.0.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[paths]` *(...(string|string&#91;&#93;))*: The property paths of elements to pick.

#### 返回结果
*(Array)*: Returns the picked values.

####示例
```js
var object = { 'a': [{ 'b': { 'c': 3 } }, 4] };

_.at(object, ['a[0].b.c', 'a[1]']);
// => [3, 4]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_createprototype-properties"><code>_.create(prototype, [properties])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12612 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.create "查看Npm包") [&#x24C9;][1]

Creates an object that inherits from the `prototype` object. If a
`properties` object is given, its own enumerable string keyed properties
are assigned to the created object.

#### 起始版本
2.3.0
#### 参数
1. `prototype` *(Object)*: The object to inherit from.
2. `[properties]` *(Object)*: The properties to assign to the object.

#### 返回结果
*(Object)*: Returns the new object.

####示例
```js
function Shape() {
  this.x = 0;
  this.y = 0;
}

function Circle() {
  Shape.call(this);
}

Circle.prototype = _.create(Shape.prototype, {
  'constructor': Circle
});

var circle = new Circle;
circle instanceof Circle;
// => true

circle instanceof Shape;
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_defaultsobject-sources"><code>_.defaults(object, [sources])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12638 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.defaults "查看Npm包") [&#x24C9;][1]

Assigns own and inherited enumerable string keyed properties of source
objects to the destination object for all destination properties that
resolve to `undefined`. Source objects are applied from left to right.
Once a property is set, additional values of the same property are ignored.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The destination object.
2. `[sources]` *(...Object)*: The source objects.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
_.defaults({ 'a': 1 }, { 'b': 2 }, { 'a': 3 });
// => { 'a': 1, 'b': 2 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_defaultsdeepobject-sources"><code>_.defaultsDeep(object, [sources])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12662 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.defaultsdeep "查看Npm包") [&#x24C9;][1]

This method is like `_.defaults` except that it recursively assigns
default properties.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
3.10.0
#### 参数
1. `object` *(Object)*: The destination object.
2. `[sources]` *(...Object)*: The source objects.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
_.defaultsDeep({ 'a': { 'b': 2 } }, { 'a': { 'b': 1, 'c': 3 } });
// => { 'a': { 'b': 2, 'c': 3 } }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_findkeyobject-predicate_identity"><code>_.findKey(object, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12702 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.findkey "查看Npm包") [&#x24C9;][1]

This method is like `_.find` except that it returns the key of the first
element `predicate` returns truthy for instead of the element itself.

#### 起始版本
1.1.0
#### 参数
1. `object` *(Object)*: The object to inspect.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(&#42;)*: Returns the key of the matched element, else `undefined`.

####示例
```js
var users = {
  'barney':  { 'age': 36, 'active': true },
  'fred':    { 'age': 40, 'active': false },
  'pebbles': { 'age': 1,  'active': true }
};

_.findKey(users, function(o) { return o.age < 40; });
// => 'barney' (iteration order is not guaranteed)

// The `_.matches` 的缩写
_.findKey(users, { 'age': 1, 'active': true });
// => 'pebbles'

// The `_.matchesProperty` 的缩写
_.findKey(users, ['active', false]);
// => 'fred'

// The `_.property` 的缩写
_.findKey(users, 'active');
// => 'barney'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_findlastkeyobject-predicate_identity"><code>_.findLastKey(object, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12741 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.findlastkey "查看Npm包") [&#x24C9;][1]

This method is like `_.findKey` except that it iterates over elements of
a collection in the opposite order.

#### 起始版本
2.0.0
#### 参数
1. `object` *(Object)*: The object to inspect.
2. `[predicate=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(&#42;)*: Returns the key of the matched element, else `undefined`.

####示例
```js
var users = {
  'barney':  { 'age': 36, 'active': true },
  'fred':    { 'age': 40, 'active': false },
  'pebbles': { 'age': 1,  'active': true }
};

_.findLastKey(users, function(o) { return o.age < 40; });
// => returns 'pebbles' assuming `_.findKey` returns 'barney'

// The `_.matches` 的缩写
_.findLastKey(users, { 'age': 36, 'active': true });
// => 'barney'

// The `_.matchesProperty` 的缩写
_.findLastKey(users, ['active', false]);
// => 'fred'

// The `_.property` 的缩写
_.findLastKey(users, 'active');
// => 'pebbles'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_forinobject-iteratee_identity"><code>_.forIn(object, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12773 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.forin "查看Npm包") [&#x24C9;][1]

Iterates over own and inherited enumerable string keyed properties of an
object and invokes `iteratee` for each property. The iteratee is invoked
with three arguments: *(value, key, object)*. Iteratee functions may exit
iteration early by explicitly returning `false`.

#### 起始版本
0.3.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forIn(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'a', 'b', then 'c' (iteration order is not guaranteed).
```
---

<!-- /div -->

<!-- div -->

<h3 id="_forinrightobject-iteratee_identity"><code>_.forInRight(object, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12805 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.forinright "查看Npm包") [&#x24C9;][1]

This method is like `_.forIn` except that it iterates over properties of
`object` in the opposite order.

#### 起始版本
2.0.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forInRight(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'c', 'b', then 'a' assuming `_.forIn` logs 'a', 'b', then 'c'.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_forownobject-iteratee_identity"><code>_.forOwn(object, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12839 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.forown "查看Npm包") [&#x24C9;][1]

Iterates over own enumerable string keyed properties of an object and
invokes `iteratee` for each property. The iteratee is invoked with three
arguments: *(value, key, object)*. Iteratee functions may exit iteration
early by explicitly returning `false`.

#### 起始版本
0.3.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forOwn(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'a' then 'b' (iteration order is not guaranteed).
```
---

<!-- /div -->

<!-- div -->

<h3 id="_forownrightobject-iteratee_identity"><code>_.forOwnRight(object, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12869 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.forownright "查看Npm包") [&#x24C9;][1]

This method is like `_.forOwn` except that it iterates over properties of
`object` in the opposite order.

#### 起始版本
2.0.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.forOwnRight(new Foo, function(value, key) {
  console.log(key);
});
// => Logs 'b' then 'a' assuming `_.forOwn` logs 'a' then 'b'.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_functionsobject"><code>_.functions(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12896 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.functions "查看Npm包") [&#x24C9;][1]

Creates an array of function property names from own enumerable properties
of `object`.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The object to inspect.

#### 返回结果
*(Array)*: Returns the function names.

####示例
```js
function Foo() {
  this.a = _.constant('a');
  this.b = _.constant('b');
}

Foo.prototype.c = _.constant('c');

_.functions(new Foo);
// => ['a', 'b']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_functionsinobject"><code>_.functionsIn(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12923 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.functionsin "查看Npm包") [&#x24C9;][1]

Creates an array of function property names from own and inherited
enumerable properties of `object`.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The object to inspect.

#### 返回结果
*(Array)*: Returns the function names.

####示例
```js
function Foo() {
  this.a = _.constant('a');
  this.b = _.constant('b');
}

Foo.prototype.c = _.constant('c');

_.functionsIn(new Foo);
// => ['a', 'b', 'c']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_getobject-path-defaultvalue"><code>_.get(object, path, [defaultValue])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12952 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.get "查看Npm包") [&#x24C9;][1]

Gets the value at `path` of `object`. If the resolved value is
`undefined`, the `defaultValue` is returned in its place.

#### 起始版本
3.7.0
#### 参数
1. `object` *(Object)*: The object to query.
2. `path` *(Array|string)*: The path of the property to get.
3. `[defaultValue]` *(&#42;)*: The value returned for `undefined` resolved values.

#### 返回结果
*(&#42;)*: Returns the resolved value.

####示例
```js
var object = { 'a': [{ 'b': { 'c': 3 } }] };

_.get(object, 'a[0].b.c');
// => 3

_.get(object, ['a', '0', 'b', 'c']);
// => 3

_.get(object, 'a.b.c', 'default');
// => 'default'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_hasobject-path"><code>_.has(object, path)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L12984 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.has "查看Npm包") [&#x24C9;][1]

Checks if `path` is a direct property of `object`.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The object to query.
2. `path` *(Array|string)*: The path to check.

#### 返回结果
*(boolean)*: Returns `true` if `path` exists, else `false`.

####示例
```js
var object = { 'a': { 'b': 2 } };
var other = _.create({ 'a': _.create({ 'b': 2 }) });

_.has(object, 'a');
// => true

_.has(object, 'a.b');
// => true

_.has(object, ['a', 'b']);
// => true

_.has(other, 'a');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_hasinobject-path"><code>_.hasIn(object, path)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13014 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.hasin "查看Npm包") [&#x24C9;][1]

Checks if `path` is a direct or inherited property of `object`.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The object to query.
2. `path` *(Array|string)*: The path to check.

#### 返回结果
*(boolean)*: Returns `true` if `path` exists, else `false`.

####示例
```js
var object = _.create({ 'a': _.create({ 'b': 2 }) });

_.hasIn(object, 'a');
// => true

_.hasIn(object, 'a.b');
// => true

_.hasIn(object, ['a', 'b']);
// => true

_.hasIn(object, 'b');
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_invertobject"><code>_.invert(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13036 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.invert "查看Npm包") [&#x24C9;][1]

Creates an object composed of the inverted keys and values of `object`.
If `object` contains duplicate values, subsequent values overwrite
property assignments of previous values.

#### 起始版本
0.7.0
#### 参数
1. `object` *(Object)*: The object to invert.

#### 返回结果
*(Object)*: Returns the new inverted object.

####示例
```js
var object = { 'a': 1, 'b': 2, 'c': 1 };

_.invert(object);
// => { '1': 'c', '2': 'b' }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_invertbyobject-iteratee_identity"><code>_.invertBy(object, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13066 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.invertby "查看Npm包") [&#x24C9;][1]

This method is like `_.invert` except that the inverted object is generated
from the results of running each element of `object` thru `iteratee`. The
corresponding inverted value of each inverted key is an array of keys
responsible for generating the inverted value. The iteratee is invoked
with one argument: *(value)*.

#### 起始版本
4.1.0
#### 参数
1. `object` *(Object)*: The object to invert.
2. `[iteratee=_.identity]` *(Function)*: The iteratee invoked per element.

#### 返回结果
*(Object)*: Returns the new inverted object.

####示例
```js
var object = { 'a': 1, 'b': 2, 'c': 1 };

_.invertBy(object);
// => { '1': ['a', 'c'], '2': ['b'] }

_.invertBy(object, function(value) {
  return 'group' + value;
});
// => { 'group1': ['a', 'c'], 'group2': ['b'] }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_invokeobject-path-args"><code>_.invoke(object, path, [args])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13092 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.invoke "查看Npm包") [&#x24C9;][1]

Invokes the method at `path` of `object`.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The object to query.
2. `path` *(Array|string)*: The path of the method to invoke.
3. `[args]` *(...&#42;)*: The arguments to invoke the method with.

#### 返回结果
*(&#42;)*: Returns the result of the invoked method.

####示例
```js
var object = { 'a': [{ 'b': { 'c': [1, 2, 3, 4] } }] };

_.invoke(object, 'a[0].b.c.slice', 1, 3);
// => [2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_keysobject"><code>_.keys(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13122 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.keys "查看Npm包") [&#x24C9;][1]

Creates an array of the own enumerable property names of `object`.
<br>
<br>
**提示:** Non-object values are coerced to objects. See the
[ES spec](http://ecma-international.org/ecma-262/7.0/#sec-object.keys)
for more details.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The object to query.

#### 返回结果
*(Array)*: Returns the array of property names.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.keys(new Foo);
// => ['a', 'b'] (iteration order is not guaranteed)

_.keys('hi');
// => ['0', '1']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_keysinobject"><code>_.keysIn(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13149 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.keysin "查看Npm包") [&#x24C9;][1]

Creates an array of the own and inherited enumerable property names of `object`.
<br>
<br>
**提示:** Non-object values are coerced to objects.

#### 起始版本
3.0.0
#### 参数
1. `object` *(Object)*: The object to query.

#### 返回结果
*(Array)*: Returns the array of property names.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.keysIn(new Foo);
// => ['a', 'b', 'c'] (iteration order is not guaranteed)
```
---

<!-- /div -->

<!-- div -->

<h3 id="_mapkeysobject-iteratee_identity"><code>_.mapKeys(object, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13174 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.mapkeys "查看Npm包") [&#x24C9;][1]

The opposite of `_.mapValues`; this method creates an object with the
same values as `object` and keys generated by running each own enumerable
string keyed property of `object` thru `iteratee`. The iteratee is invoked
with three arguments: *(value, key, object)*.

#### 起始版本
3.8.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Object)*: Returns the new mapped object.

####示例
```js
_.mapKeys({ 'a': 1, 'b': 2 }, function(value, key) {
  return key + value;
});
// => { 'a1': 1, 'b2': 2 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_mapvaluesobject-iteratee_identity"><code>_.mapValues(object, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13212 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.mapvalues "查看Npm包") [&#x24C9;][1]

Creates an object with the same keys as `object` and values generated
by running each own enumerable string keyed property of `object` thru
`iteratee`. The iteratee is invoked with three arguments:<br>
*(value, key, object)*.

#### 起始版本
2.4.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Object)*: Returns the new mapped object.

####示例
```js
var users = {
  'fred':    { 'user': 'fred',    'age': 40 },
  'pebbles': { 'user': 'pebbles', 'age': 1 }
};

_.mapValues(users, function(o) { return o.age; });
// => { 'fred': 40, 'pebbles': 1 } (iteration order is not guaranteed)

// The `_.property` 的缩写
_.mapValues(users, 'age');
// => { 'fred': 40, 'pebbles': 1 } (iteration order is not guaranteed)
```
---

<!-- /div -->

<!-- div -->

<h3 id="_mergeobject-sources"><code>_.merge(object, [sources])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13253 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.merge "查看Npm包") [&#x24C9;][1]

This method is like `_.assign` except that it recursively merges own and
inherited enumerable string keyed properties of source objects into the
destination object. Source properties that resolve to `undefined` are
skipped if a destination value exists. Array and plain object properties
are merged recursively. Other objects and value types are overridden by
assignment. Source objects are applied from left to right. Subsequent
sources overwrite property assignments of previous sources.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
0.5.0
#### 参数
1. `object` *(Object)*: The destination object.
2. `[sources]` *(...Object)*: The source objects.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
var object = {
  'a': [{ 'b': 2 }, { 'd': 4 }]
};

var other = {
  'a': [{ 'c': 3 }, { 'e': 5 }]
};

_.merge(object, other);
// => { 'a': [{ 'b': 2, 'c': 3 }, { 'd': 4, 'e': 5 }] }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_mergewithobject-sources-customizer"><code>_.mergeWith(object, sources, customizer)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13288 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.mergewith "查看Npm包") [&#x24C9;][1]

This method is like `_.merge` except that it accepts `customizer` which
is invoked to produce the merged values of the destination and source
properties. If `customizer` returns `undefined`, merging is handled by the
method instead. The `customizer` is invoked with six arguments:<br>
*(objValue, srcValue, key, object, source, stack)*.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The destination object.
2. `sources` *(...Object)*: The source objects.
3. `customizer` *(Function)*: The function to customize assigned values.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
function customizer(objValue, srcValue) {
  if (_.isArray(objValue)) {
    return objValue.concat(srcValue);
  }
}

var object = { 'a': [1], 'b': [2] };
var other = { 'a': [3], 'b': [4] };

_.mergeWith(object, other, customizer);
// => { 'a': [1, 3], 'b': [2, 4] }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_omitobject-props"><code>_.omit(object, [props])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13311 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.omit "查看Npm包") [&#x24C9;][1]

The opposite of `_.pick`; this method creates an object composed of the
own and inherited enumerable string keyed properties of `object` that are
not omitted.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The source object.
2. `[props]` *(...(string|string&#91;&#93;))*: The property identifiers to omit.

#### 返回结果
*(Object)*: Returns the new object.

####示例
```js
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.omit(object, ['a', 'c']);
// => { 'b': '2' }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_omitbyobject-predicate_identity"><code>_.omitBy(object, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13339 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.omitby "查看Npm包") [&#x24C9;][1]

The opposite of `_.pickBy`; this method creates an object composed of
the own and inherited enumerable string keyed properties of `object` that
`predicate` doesn't return truthy for. The predicate is invoked with two
arguments: *(value, key)*.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The source object.
2. `[predicate=_.identity]` *(Function)*: The function invoked per property.

#### 返回结果
*(Object)*: Returns the new object.

####示例
```js
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.omitBy(object, _.isNumber);
// => { 'b': '2' }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_pickobject-props"><code>_.pick(object, [props])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13360 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pick "查看Npm包") [&#x24C9;][1]

Creates an object composed of the picked `object` properties.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The source object.
2. `[props]` *(...(string|string&#91;&#93;))*: The property identifiers to pick.

#### 返回结果
*(Object)*: Returns the new object.

####示例
```js
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.pick(object, ['a', 'c']);
// => { 'a': 1, 'c': 3 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_pickbyobject-predicate_identity"><code>_.pickBy(object, [predicate=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13382 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pickby "查看Npm包") [&#x24C9;][1]

Creates an object composed of the `object` properties `predicate` returns
truthy for. The predicate is invoked with two arguments: *(value, key)*.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The source object.
2. `[predicate=_.identity]` *(Function)*: The function invoked per property.

#### 返回结果
*(Object)*: Returns the new object.

####示例
```js
var object = { 'a': 1, 'b': '2', 'c': 3 };

_.pickBy(object, _.isNumber);
// => { 'a': 1, 'c': 3 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_resultobject-path-defaultvalue"><code>_.result(object, path, [defaultValue])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13415 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.result "查看Npm包") [&#x24C9;][1]

This method is like `_.get` except that if the resolved value is a
function it's invoked with the `this` binding of its parent object and
its result is returned.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The object to query.
2. `path` *(Array|string)*: The path of the property to resolve.
3. `[defaultValue]` *(&#42;)*: The value returned for `undefined` resolved values.

#### 返回结果
*(&#42;)*: Returns the resolved value.

####示例
```js
var object = { 'a': [{ 'b': { 'c1': 3, 'c2': _.constant(4) } }] };

_.result(object, 'a[0].b.c1');
// => 3

_.result(object, 'a[0].b.c2');
// => 4

_.result(object, 'a[0].b.c3', 'default');
// => 'default'

_.result(object, 'a[0].b.c3', _.constant('default'));
// => 'default'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_setobject-path-value"><code>_.set(object, path, value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13465 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.set "查看Npm包") [&#x24C9;][1]

Sets the value at `path` of `object`. If a portion of `path` doesn't exist,
it's created. Arrays are created for missing index properties while objects
are created for all other missing properties. Use `_.setWith` to customize
`path` creation.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
3.7.0
#### 参数
1. `object` *(Object)*: The object to modify.
2. `path` *(Array|string)*: The path of the property to set.
3. `value` *(&#42;)*: The value to set.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
var object = { 'a': [{ 'b': { 'c': 3 } }] };

_.set(object, 'a[0].b.c', 4);
console.log(object.a[0].b.c);
// => 4

_.set(object, ['x', '0', 'y', 'z'], 5);
console.log(object.x[0].y.z);
// => 5
```
---

<!-- /div -->

<!-- div -->

<h3 id="_setwithobject-path-value-customizer"><code>_.setWith(object, path, value, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13493 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.setwith "查看Npm包") [&#x24C9;][1]

This method is like `_.set` except that it accepts `customizer` which is
invoked to produce the objects of `path`.  If `customizer` returns `undefined`
path creation is handled by the method instead. The `customizer` is invoked
with three arguments: *(nsValue, key, nsObject)*.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The object to modify.
2. `path` *(Array|string)*: The path of the property to set.
3. `value` *(&#42;)*: The value to set.
4. `[customizer]` *(Function)*: The function to customize assigned values.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
var object = {};

_.setWith(object, '[0][1]', 'a', Object);
// => { '0': { '1': 'a' } }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_topairsobject"><code>_.toPairs(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13522 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.topairs "查看Npm包") [&#x24C9;][1]

Creates an array of own enumerable string keyed-value pairs for `object`
which can be consumed by `_.fromPairs`. If `object` is a map or set, its
entries are returned.

#### 起始版本
4.0.0
#### Aliases
*_.entries*

#### 参数
1. `object` *(Object)*: The object to query.

#### 返回结果
*(Array)*: Returns the key-value pairs.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.toPairs(new Foo);
// => [['a', 1], ['b', 2]] (iteration order is not guaranteed)
```
---

<!-- /div -->

<!-- div -->

<h3 id="_topairsinobject"><code>_.toPairsIn(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13548 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.topairsin "查看Npm包") [&#x24C9;][1]

Creates an array of own and inherited enumerable string keyed-value pairs
for `object` which can be consumed by `_.fromPairs`. If `object` is a map
or set, its entries are returned.

#### 起始版本
4.0.0
#### Aliases
*_.entriesIn*

#### 参数
1. `object` *(Object)*: The object to query.

#### 返回结果
*(Array)*: Returns the key-value pairs.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.toPairsIn(new Foo);
// => [['a', 1], ['b', 2], ['c', 3]] (iteration order is not guaranteed)
```
---

<!-- /div -->

<!-- div -->

<h3 id="_transformobject-iteratee_identity-accumulator"><code>_.transform(object, [iteratee=_.identity], [accumulator])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13580 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.transform "查看Npm包") [&#x24C9;][1]

An alternative to `_.reduce`; this method transforms `object` to a new
`accumulator` object which is the result of running each of its own
enumerable string keyed properties thru `iteratee`, with each invocation
potentially mutating the `accumulator` object. If `accumulator` is not
provided, a new object with the same `[[Prototype]]` will be used. The
iteratee is invoked with four arguments: *(accumulator, value, key, object)*.
Iteratee functions may exit iteration early by explicitly returning `false`.

#### 起始版本
1.3.0
#### 参数
1. `object` *(Object)*: The object to iterate over.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.
3. `[accumulator]` *(&#42;)*: The custom accumulator value.

#### 返回结果
*(&#42;)*: Returns the accumulated value.

####示例
```js
_.transform([2, 3, 4], function(result, n) {
  result.push(n *= n);
  return n % 2 == 0;
}, []);
// => [4, 9]

_.transform({ 'a': 1, 'b': 2, 'c': 1 }, function(result, value, key) {
  (result[value] || (result[value] = [])).push(key);
}, {});
// => { '1': ['a', 'c'], '2': ['b'] }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unsetobject-path"><code>_.unset(object, path)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13629 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.unset "查看Npm包") [&#x24C9;][1]

Removes the property at `path` of `object`.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.0.0
#### 参数
1. `object` *(Object)*: The object to modify.
2. `path` *(Array|string)*: The path of the property to unset.

#### 返回结果
*(boolean)*: Returns `true` if the property is deleted, else `false`.

####示例
```js
var object = { 'a': [{ 'b': { 'c': 7 } }] };
_.unset(object, 'a[0].b.c');
// => true

console.log(object);
// => { 'a': [{ 'b': {} }] };

_.unset(object, ['a', '0', 'b', 'c']);
// => true

console.log(object);
// => { 'a': [{ 'b': {} }] };
```
---

<!-- /div -->

<!-- div -->

<h3 id="_updateobject-path-updater"><code>_.update(object, path, updater)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13660 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.update "查看Npm包") [&#x24C9;][1]

This method is like `_.set` except that accepts `updater` to produce the
value to set. Use `_.updateWith` to customize `path` creation. The `updater`
is invoked with one argument: *(value)*.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.6.0
#### 参数
1. `object` *(Object)*: The object to modify.
2. `path` *(Array|string)*: The path of the property to set.
3. `updater` *(Function)*: The function to produce the updated value.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
var object = { 'a': [{ 'b': { 'c': 3 } }] };

_.update(object, 'a[0].b.c', function(n) { return n * n; });
console.log(object.a[0].b.c);
// => 9

_.update(object, 'x[0].y.z', function(n) { return n ? n + 1 : 0; });
console.log(object.x[0].y.z);
// => 0
```
---

<!-- /div -->

<!-- div -->

<h3 id="_updatewithobject-path-updater-customizer"><code>_.updateWith(object, path, updater, [customizer])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13688 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.updatewith "查看Npm包") [&#x24C9;][1]

This method is like `_.update` except that it accepts `customizer` which is
invoked to produce the objects of `path`.  If `customizer` returns `undefined`
path creation is handled by the method instead. The `customizer` is invoked
with three arguments: *(nsValue, key, nsObject)*.
<br>
<br>
**提示:** This method mutates `object`.

#### 起始版本
4.6.0
#### 参数
1. `object` *(Object)*: The object to modify.
2. `path` *(Array|string)*: The path of the property to set.
3. `updater` *(Function)*: The function to produce the updated value.
4. `[customizer]` *(Function)*: The function to customize assigned values.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
var object = {};

_.updateWith(object, '[0][1]', _.constant('a'), Object);
// => { '0': { '1': 'a' } }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_valuesobject"><code>_.values(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13719 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.values "查看Npm包") [&#x24C9;][1]

Creates an array of the own enumerable string keyed property values of `object`.
<br>
<br>
**提示:** Non-object values are coerced to objects.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The object to query.

#### 返回结果
*(Array)*: Returns the array of property values.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.values(new Foo);
// => [1, 2] (iteration order is not guaranteed)

_.values('hi');
// => ['h', 'i']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_valuesinobject"><code>_.valuesIn(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13747 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.valuesin "查看Npm包") [&#x24C9;][1]

Creates an array of the own and inherited enumerable string keyed property
values of `object`.
<br>
<br>
**提示:** Non-object values are coerced to objects.

#### 起始版本
3.0.0
#### 参数
1. `object` *(Object)*: The object to query.

#### 返回结果
*(Array)*: Returns the array of property values.

####示例
```js
function Foo() {
  this.a = 1;
  this.b = 2;
}

Foo.prototype.c = 3;

_.valuesIn(new Foo);
// => [1, 2, 3] (iteration order is not guaranteed)
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Seq” Methods`

<!-- div -->

<h3 id="_value"><code>_(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1644 "查看源码") [&#x24C9;][1]

Creates a `lodash` object which wraps `value` to enable implicit method
chain sequences. Methods that operate on and return arrays, collections,
and functions can be chained together. Methods that retrieve a single value
or may return a primitive value will automatically end the chain sequence
and return the unwrapped value. Otherwise, the value must be unwrapped
with `_#value`.
<br>
<br>
Explicit chain sequences, which must be unwrapped with `_#value`, may be
enabled using `_.chain`.
<br>
<br>
The execution of chained methods is lazy, that is, it's deferred until
`_#value` is implicitly or explicitly called.
<br>
<br>
Lazy evaluation allows several methods to support shortcut fusion.
Shortcut fusion is an optimization to merge iteratee calls; this avoids
the creation of intermediate arrays and can greatly reduce the number of
iteratee executions. Sections of a chain sequence qualify for shortcut
fusion if the section is applied to an array of at least `200` elements
and any iteratees accept only one argument. The heuristic for whether a
section qualifies for shortcut fusion is subject to change.
<br>
<br>
Chaining is supported in custom builds as long as the `_#value` method is
directly or indirectly included in the build.
<br>
<br>
In addition to lodash methods, wrappers have `Array` and `String` methods.
<br>
<br>
The wrapper `Array` methods are:<br>
`concat`, `join`, `pop`, `push`, `shift`, `sort`, `splice`, and `unshift`
<br>
<br>
The wrapper `String` methods are:<br>
`replace` and `split`
<br>
<br>
The wrapper methods that support shortcut fusion are:<br>
`at`, `compact`, `drop`, `dropRight`, `dropWhile`, `filter`, `find`,
`findLast`, `head`, `initial`, `last`, `map`, `reject`, `reverse`, `slice`,
`tail`, `take`, `takeRight`, `takeRightWhile`, `takeWhile`, and `toArray`
<br>
<br>
The chainable wrapper methods are:<br>
`after`, `ary`, `assign`, `assignIn`, `assignInWith`, `assignWith`, `at`,
`before`, `bind`, `bindAll`, `bindKey`, `castArray`, `chain`, `chunk`,
`commit`, `compact`, `concat`, `conforms`, `constant`, `countBy`, `create`,
`curry`, `debounce`, `defaults`, `defaultsDeep`, `defer`, `delay`,
`difference`, `differenceBy`, `differenceWith`, `drop`, `dropRight`,
`dropRightWhile`, `dropWhile`, `extend`, `extendWith`, `fill`, `filter`,
`flatMap`, `flatMapDeep`, `flatMapDepth`, `flatten`, `flattenDeep`,
`flattenDepth`, `flip`, `flow`, `flowRight`, `fromPairs`, `functions`,
`functionsIn`, `groupBy`, `initial`, `intersection`, `intersectionBy`,
`intersectionWith`, `invert`, `invertBy`, `invokeMap`, `iteratee`, `keyBy`,
`keys`, `keysIn`, `map`, `mapKeys`, `mapValues`, `matches`, `matchesProperty`,
`memoize`, `merge`, `mergeWith`, `method`, `methodOf`, `mixin`, `negate`,
`nthArg`, `omit`, `omitBy`, `once`, `orderBy`, `over`, `overArgs`,
`overEvery`, `overSome`, `partial`, `partialRight`, `partition`, `pick`,
`pickBy`, `plant`, `property`, `propertyOf`, `pull`, `pullAll`, `pullAllBy`,
`pullAllWith`, `pullAt`, `push`, `range`, `rangeRight`, `rearg`, `reject`,
`remove`, `rest`, `reverse`, `sampleSize`, `set`, `setWith`, `shuffle`,
`slice`, `sort`, `sortBy`, `splice`, `spread`, `tail`, `take`, `takeRight`,
`takeRightWhile`, `takeWhile`, `tap`, `throttle`, `thru`, `toArray`,
`toPairs`, `toPairsIn`, `toPath`, `toPlainObject`, `transform`, `unary`,
`union`, `unionBy`, `unionWith`, `uniq`, `uniqBy`, `uniqWith`, `unset`,
`unshift`, `unzip`, `unzipWith`, `update`, `updateWith`, `values`,
`valuesIn`, `without`, `wrap`, `xor`, `xorBy`, `xorWith`, `zip`,
`zipObject`, `zipObjectDeep`, and `zipWith`
<br>
<br>
The wrapper methods that are **not** chainable by default are:<br>
`add`, `attempt`, `camelCase`, `capitalize`, `ceil`, `clamp`, `clone`,
`cloneDeep`, `cloneDeepWith`, `cloneWith`, `conformsTo`, `deburr`,
`defaultTo`, `divide`, `each`, `eachRight`, `endsWith`, `eq`, `escape`,
`escapeRegExp`, `every`, `find`, `findIndex`, `findKey`, `findLast`,
`findLastIndex`, `findLastKey`, `first`, `floor`, `forEach`, `forEachRight`,
`forIn`, `forInRight`, `forOwn`, `forOwnRight`, `get`, `gt`, `gte`, `has`,
`hasIn`, `head`, `identity`, `includes`, `indexOf`, `inRange`, `invoke`,
`isArguments`, `isArray`, `isArrayBuffer`, `isArrayLike`, `isArrayLikeObject`,
`isBoolean`, `isBuffer`, `isDate`, `isElement`, `isEmpty`, `isEqual`,
`isEqualWith`, `isError`, `isFinite`, `isFunction`, `isInteger`, `isLength`,
`isMap`, `isMatch`, `isMatchWith`, `isNaN`, `isNative`, `isNil`, `isNull`,
`isNumber`, `isObject`, `isObjectLike`, `isPlainObject`, `isRegExp`,
`isSafeInteger`, `isSet`, `isString`, `isUndefined`, `isTypedArray`,
`isWeakMap`, `isWeakSet`, `join`, `kebabCase`, `last`, `lastIndexOf`,
`lowerCase`, `lowerFirst`, `lt`, `lte`, `max`, `maxBy`, `mean`, `meanBy`,
`min`, `minBy`, `multiply`, `noConflict`, `noop`, `now`, `nth`, `pad`,
`padEnd`, `padStart`, `parseInt`, `pop`, `random`, `reduce`, `reduceRight`,
`repeat`, `result`, `round`, `runInContext`, `sample`, `shift`, `size`,
`snakeCase`, `some`, `sortedIndex`, `sortedIndexBy`, `sortedLastIndex`,
`sortedLastIndexBy`, `startCase`, `startsWith`, `stubArray`, `stubFalse`,
`stubObject`, `stubString`, `stubTrue`, `subtract`, `sum`, `sumBy`,
`template`, `times`, `toFinite`, `toInteger`, `toJSON`, `toLength`,
`toLower`, `toNumber`, `toSafeInteger`, `toString`, `toUpper`, `trim`,
`trimEnd`, `trimStart`, `truncate`, `unescape`, `uniqueId`, `upperCase`,
`upperFirst`, `value`, and `words`

#### 参数
1. `value` *(&#42;)*: The value to wrap in a `lodash` instance.

#### 返回结果
*(Object)*: Returns the new `lodash` wrapper instance.

####示例
```js
function square(n) {
  return n * n;
}

var wrapped = _([1, 2, 3]);

// Returns an unwrapped value.
wrapped.reduce(_.add);
// => 6

// Returns a wrapped value.
var squares = wrapped.map(square);

_.isArray(squares);
// => false

_.isArray(squares.value());
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_chainvalue"><code>_.chain(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8589 "查看源码") [&#x24C9;][1]

Creates a `lodash` wrapper instance that wraps `value` with explicit method
chain sequences enabled. The result of such sequences must be unwrapped
with `_#value`.

#### 起始版本
1.3.0
#### 参数
1. `value` *(&#42;)*: The value to wrap.

#### 返回结果
*(Object)*: Returns the new `lodash` wrapper instance.

####示例
```js
var users = [
  { 'user': 'barney',  'age': 36 },
  { 'user': 'fred',    'age': 40 },
  { 'user': 'pebbles', 'age': 1 }
];

var youngest = _
  .chain(users)
  .sortBy('age')
  .map(function(o) {
    return o.user + ' is ' + o.age;
  })
  .head()
  .value();
// => 'pebbles is 1'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tapvalue-interceptor"><code>_.tap(value, interceptor)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8618 "查看源码") [&#x24C9;][1]

This method invokes `interceptor` and returns `value`. The interceptor
is invoked with one argument; *(value)*. The purpose of this method is to
"tap into" a method chain sequence in order to modify intermediate results.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: The value to provide to `interceptor`.
2. `interceptor` *(Function)*: The function to invoke.

#### 返回结果
*(&#42;)*: Returns `value`.

####示例
```js
_([1, 2, 3])
 .tap(function(array) {
   // Mutate input array.
   array.pop();
 })
 .reverse()
 .value();
// => [2, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_thruvalue-interceptor"><code>_.thru(value, interceptor)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8646 "查看源码") [&#x24C9;][1]

This method is like `_.tap` except that it returns the result of `interceptor`.
The purpose of this method is to "pass thru" values replacing intermediate
results in a method chain sequence.

#### 起始版本
3.0.0
#### 参数
1. `value` *(&#42;)*: The value to provide to `interceptor`.
2. `interceptor` *(Function)*: The function to invoke.

#### 返回结果
*(&#42;)*: Returns the result of `interceptor`.

####示例
```js
_('  abc  ')
 .chain()
 .trim()
 .thru(function(value) {
   return [value];
 })
 .value();
// => ['abc']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypesymboliterator"><code>_.prototype[Symbol.iterator]()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8801 "查看源码") [&#x24C9;][1]

Enables the wrapper to be iterable.

#### 起始版本
4.0.0
#### 返回结果
*(Object)*: Returns the wrapper object.

####示例
```js
var wrapped = _([1, 2]);

wrapped[Symbol.iterator]() === wrapped;
// => true

Array.from(wrapped);
// => [1, 2]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypeatpaths"><code>_.prototype.at([paths])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8666 "查看源码") [&#x24C9;][1]

This method is the wrapper version of `_.at`.

#### 起始版本
1.0.0
#### 参数
1. `[paths]` *(...(string|string&#91;&#93;))*: The property paths of elements to pick.

#### 返回结果
*(Object)*: Returns the new `lodash` wrapper instance.

####示例
```js
var object = { 'a': [{ 'b': { 'c': 3 } }, 4] };

_(object).at(['a[0].b.c', 'a[1]']).value();
// => [3, 4]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypechain"><code>_.prototype.chain()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8717 "查看源码") [&#x24C9;][1]

Creates a `lodash` wrapper instance with explicit method chain sequences enabled.

#### 起始版本
0.1.0
#### 返回结果
*(Object)*: Returns the new `lodash` wrapper instance.

####示例
```js
var users = [
  { 'user': 'barney', 'age': 36 },
  { 'user': 'fred',   'age': 40 }
];

// A sequence without explicit chaining.
_(users).head();
// => { 'user': 'barney', 'age': 36 }

// A sequence with explicit chaining.
_(users)
  .chain()
  .head()
  .pick('user')
  .value();
// => { 'user': 'barney' }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypecommit"><code>_.prototype.commit()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8747 "查看源码") [&#x24C9;][1]

Executes the chain sequence and returns the wrapped result.

#### 起始版本
3.2.0
#### 返回结果
*(Object)*: Returns the new `lodash` wrapper instance.

####示例
```js
var array = [1, 2];
var wrapped = _(array).push(3);

console.log(array);
// => [1, 2]

wrapped = wrapped.commit();
console.log(array);
// => [1, 2, 3]

wrapped.last();
// => 3

console.log(array);
// => [1, 2, 3]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypenext"><code>_.prototype.next()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8773 "查看源码") [&#x24C9;][1]

Gets the next value on a wrapped object following the
[iterator protocol](https://mdn.io/iteration_protocols#iterator).

#### 起始版本
4.0.0
#### 返回结果
*(Object)*: Returns the next iterator value.

####示例
```js
var wrapped = _([1, 2]);

wrapped.next();
// => { 'done': false, 'value': 1 }

wrapped.next();
// => { 'done': false, 'value': 2 }

wrapped.next();
// => { 'done': true, 'value': undefined }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypeplantvalue"><code>_.prototype.plant(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8829 "查看源码") [&#x24C9;][1]

Creates a clone of the chain sequence planting `value` as the wrapped value.

#### 起始版本
3.2.0
#### 参数
1. `value` *(&#42;)*: The value to plant.

#### 返回结果
*(Object)*: Returns the new `lodash` wrapper instance.

####示例
```js
function square(n) {
  return n * n;
}

var wrapped = _([1, 2]).map(square);
var other = wrapped.plant([3, 4]);

other.value();
// => [9, 16]

wrapped.value();
// => [1, 4]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypereverse"><code>_.prototype.reverse()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8869 "查看源码") [&#x24C9;][1]

This method is the wrapper version of `_.reverse`.
<br>
<br>
**提示:** This method mutates the wrapped array.

#### 起始版本
0.1.0
#### 返回结果
*(Object)*: Returns the new `lodash` wrapper instance.

####示例
```js
var array = [1, 2, 3];

_(array).reverse().value()
// => [3, 2, 1]

console.log(array);
// => [3, 2, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_prototypevalue"><code>_.prototype.value()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L8901 "查看源码") [&#x24C9;][1]

Executes the chain sequence to resolve the unwrapped value.

#### 起始版本
0.1.0
#### Aliases
*_.prototype.toJSON, _.prototype.valueOf*

#### 返回结果
*(&#42;)*: Returns the resolved unwrapped value.

####示例
```js
_([1, 2, 3]).value();
// => [1, 2, 3]
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“String” Methods`

<!-- div -->

<h3 id="_camelcasestring"><code>_.camelCase([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13930 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.camelcase "查看Npm包") [&#x24C9;][1]

Converts `string` to [camel case](https://en.wikipedia.org/wiki/CamelCase).

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the camel cased string.

####示例
```js
_.camelCase('Foo Bar');
// => 'fooBar'

_.camelCase('--foo-bar--');
// => 'fooBar'

_.camelCase('__FOO_BAR__');
// => 'fooBar'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_capitalizestring"><code>_.capitalize([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13950 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.capitalize "查看Npm包") [&#x24C9;][1]

Converts the first character of `string` to upper case and the remaining
to lower case.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to capitalize.

#### 返回结果
*(string)*: Returns the capitalized string.

####示例
```js
_.capitalize('FRED');
// => 'Fred'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_deburrstring"><code>_.deburr([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L13972 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.deburr "查看Npm包") [&#x24C9;][1]

Deburrs `string` by converting
[Latin-1 Supplement](https://en.wikipedia.org/wiki/Latin-1_Supplement_(Unicode_block)#Character_table)
and [Latin Extended-A](https://en.wikipedia.org/wiki/Latin_Extended-A)
letters to basic Latin letters and removing
[combining diacritical marks](https://en.wikipedia.org/wiki/Combining_Diacritical_Marks).

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to deburr.

#### 返回结果
*(string)*: Returns the deburred string.

####示例
```js
_.deburr('déjà vu');
// => 'deja vu'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_endswithstring-target-positionstringlength"><code>_.endsWith([string=''], [target], [position=string.length])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14000 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.endswith "查看Npm包") [&#x24C9;][1]

Checks if `string` ends with the given target string.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to inspect.
2. `[target]` *(string)*: The string to search for.
3. `[position=string.length]` *(number)*: The position to search up to.

#### 返回结果
*(boolean)*: Returns `true` if `string` ends with `target`, else `false`.

####示例
```js
_.endsWith('abc', 'c');
// => true

_.endsWith('abc', 'b');
// => false

_.endsWith('abc', 'b', 2);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_escapestring"><code>_.escape([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14042 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.escape "查看Npm包") [&#x24C9;][1]

Converts the characters "&", "<", ">", '"', and "'" in `string` to their
corresponding HTML entities.
<br>
<br>
**提示:** No other characters are escaped. To escape additional
characters use a third-party library like [_he_](https://mths.be/he).
<br>
<br>
Though the ">" character is escaped for symmetry, characters like
">" and "/" don't need escaping in HTML and have no special meaning
unless they're part of a tag or unquoted attribute value. See
[Mathias Bynens's article](https://mathiasbynens.be/notes/ambiguous-ampersands)
*(under "semi-related fun fact")* for more details.
<br>
<br>
When working with HTML you should always
[quote attribute values](http://wonko.com/post/html-escaping) to reduce
XSS vectors.

#### 起始版本
0.1.0
#### 参数
1. `[string='']` *(string)*: The string to escape.

#### 返回结果
*(string)*: Returns the escaped string.

####示例
```js
_.escape('fred, barney, & pebbles');
// => 'fred, barney, &amp; pebbles'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_escaperegexpstring"><code>_.escapeRegExp([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14064 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.escaperegexp "查看Npm包") [&#x24C9;][1]

Escapes the `RegExp` special characters "^", "$", "\", ".", "*", "+",
"?", "(", ")", "[", "]", "{", "}", and "|" in `string`.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to escape.

#### 返回结果
*(string)*: Returns the escaped string.

####示例
```js
_.escapeRegExp('[lodash](https://lodash.com/)');
// => '\[lodash\]\(https://lodash\.com/\)'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_kebabcasestring"><code>_.kebabCase([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14092 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.kebabcase "查看Npm包") [&#x24C9;][1]

Converts `string` to
[kebab case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles).

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the kebab cased string.

####示例
```js
_.kebabCase('Foo Bar');
// => 'foo-bar'

_.kebabCase('fooBar');
// => 'foo-bar'

_.kebabCase('__FOO_BAR__');
// => 'foo-bar'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_lowercasestring"><code>_.lowerCase([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14116 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.lowercase "查看Npm包") [&#x24C9;][1]

Converts `string`, as space separated words, to lower case.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the lower cased string.

####示例
```js
_.lowerCase('--Foo-Bar--');
// => 'foo bar'

_.lowerCase('fooBar');
// => 'foo bar'

_.lowerCase('__FOO_BAR__');
// => 'foo bar'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_lowerfirststring"><code>_.lowerFirst([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14137 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.lowerfirst "查看Npm包") [&#x24C9;][1]

Converts the first character of `string` to lower case.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the converted string.

####示例
```js
_.lowerFirst('Fred');
// => 'fred'

_.lowerFirst('FRED');
// => 'fRED'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_padstring-length0-chars"><code>_.pad([string=''], [length=0], [chars=' '])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14162 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.pad "查看Npm包") [&#x24C9;][1]

Pads `string` on the left and right sides if it's shorter than `length`.
Padding characters are truncated if they can't be evenly divided by `length`.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to pad.
2. `[length=0]` *(number)*: The padding length.
3. `[chars=' ']` *(string)*: The string used as padding.

#### 返回结果
*(string)*: Returns the padded string.

####示例
```js
_.pad('abc', 8);
// => '  abc   '

_.pad('abc', 8, '_-');
// => '_-abc_-_'

_.pad('abc', 3);
// => 'abc'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_padendstring-length0-chars"><code>_.padEnd([string=''], [length=0], [chars=' '])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14201 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.padend "查看Npm包") [&#x24C9;][1]

Pads `string` on the right side if it's shorter than `length`. Padding
characters are truncated if they exceed `length`.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to pad.
2. `[length=0]` *(number)*: The padding length.
3. `[chars=' ']` *(string)*: The string used as padding.

#### 返回结果
*(string)*: Returns the padded string.

####示例
```js
_.padEnd('abc', 6);
// => 'abc   '

_.padEnd('abc', 6, '_-');
// => 'abc_-_'

_.padEnd('abc', 3);
// => 'abc'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_padstartstring-length0-chars"><code>_.padStart([string=''], [length=0], [chars=' '])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14234 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.padstart "查看Npm包") [&#x24C9;][1]

Pads `string` on the left side if it's shorter than `length`. Padding
characters are truncated if they exceed `length`.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to pad.
2. `[length=0]` *(number)*: The padding length.
3. `[chars=' ']` *(string)*: The string used as padding.

#### 返回结果
*(string)*: Returns the padded string.

####示例
```js
_.padStart('abc', 6);
// => '   abc'

_.padStart('abc', 6, '_-');
// => '_-_abc'

_.padStart('abc', 3);
// => 'abc'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_parseintstring-radix10"><code>_.parseInt(string, [radix=10])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14268 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.parseint "查看Npm包") [&#x24C9;][1]

Converts `string` to an integer of the specified radix. If `radix` is
`undefined` or `0`, a `radix` of `10` is used unless `value` is a
hexadecimal, in which case a `radix` of `16` is used.
<br>
<br>
**提示:** This method aligns with the
[ES5 implementation](https://es5.github.io/#x15.1.2.2) of `parseInt`.

#### 起始版本
1.1.0
#### 参数
1. `string` *(string)*: The string to convert.
2. `[radix=10]` *(number)*: The radix to interpret `value` by.

#### 返回结果
*(number)*: Returns the converted integer.

####示例
```js
_.parseInt('08');
// => 8

_.map(['6', '08', '10'], _.parseInt);
// => [6, 8, 10]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_repeatstring-n1"><code>_.repeat([string=''], [n=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14299 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.repeat "查看Npm包") [&#x24C9;][1]

Repeats the given string `n` times.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to repeat.
2. `[n=1]` *(number)*: The number of times to repeat the string.

#### 返回结果
*(string)*: Returns the repeated string.

####示例
```js
_.repeat('*', 3);
// => '***'

_.repeat('abc', 2);
// => 'abcabc'

_.repeat('abc', 0);
// => ''
```
---

<!-- /div -->

<!-- div -->

<h3 id="_replacestring-pattern-replacement"><code>_.replace([string=''], pattern, replacement)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14327 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.replace "查看Npm包") [&#x24C9;][1]

Replaces matches for `pattern` in `string` with `replacement`.
<br>
<br>
**提示:** This method is based on
[`String#replace`](https://mdn.io/String/replace).

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to modify.
2. `pattern` *(RegExp|string)*: The pattern to replace.
3. `replacement` *(Function|string)*: The match replacement.

#### 返回结果
*(string)*: Returns the modified string.

####示例
```js
_.replace('Hi Fred', 'Fred', 'Barney');
// => 'Hi Barney'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_snakecasestring"><code>_.snakeCase([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14355 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.snakecase "查看Npm包") [&#x24C9;][1]

Converts `string` to
[snake case](https://en.wikipedia.org/wiki/Snake_case).

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the snake cased string.

####示例
```js
_.snakeCase('Foo Bar');
// => 'foo_bar'

_.snakeCase('fooBar');
// => 'foo_bar'

_.snakeCase('--FOO-BAR--');
// => 'foo_bar'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_splitstring-separator-limit"><code>_.split([string=''], separator, [limit])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14378 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.split "查看Npm包") [&#x24C9;][1]

Splits `string` by `separator`.
<br>
<br>
**提示:** This method is based on
[`String#split`](https://mdn.io/String/split).

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to split.
2. `separator` *(RegExp|string)*: The separator pattern to split by.
3. `[limit]` *(number)*: The length to truncate results to.

#### 返回结果
*(Array)*: Returns the string segments.

####示例
```js
_.split('a-b-c', '-', 2);
// => ['a', 'b']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_startcasestring"><code>_.startCase([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14420 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.startcase "查看Npm包") [&#x24C9;][1]

Converts `string` to
[start case](https://en.wikipedia.org/wiki/Letter_case#Stylistic_or_specialised_usage).

#### 起始版本
3.1.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the start cased string.

####示例
```js
_.startCase('--foo-bar--');
// => 'Foo Bar'

_.startCase('fooBar');
// => 'Foo Bar'

_.startCase('__FOO_BAR__');
// => 'FOO BAR'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_startswithstring-target-position0"><code>_.startsWith([string=''], [target], [position=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14447 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.startswith "查看Npm包") [&#x24C9;][1]

Checks if `string` starts with the given target string.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to inspect.
2. `[target]` *(string)*: The string to search for.
3. `[position=0]` *(number)*: The position to search from.

#### 返回结果
*(boolean)*: Returns `true` if `string` starts with `target`, else `false`.

####示例
```js
_.startsWith('abc', 'a');
// => true

_.startsWith('abc', 'b');
// => false

_.startsWith('abc', 'b', 1);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_templatestring-options"><code>_.template([string=''], [options={}])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14558 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.template "查看Npm包") [&#x24C9;][1]

Creates a compiled template function that can interpolate data properties
in "interpolate" delimiters, HTML-escape interpolated data properties in
"escape" delimiters, and execute JavaScript in "evaluate" delimiters. Data
properties may be accessed as free variables in the template. If a setting
object is given, it takes precedence over `_.templateSettings` values.
<br>
<br>
**提示:** In the development build `_.template` utilizes
[sourceURLs](http://www.html5rocks.com/en/tutorials/developertools/sourcemaps/#toc-sourceurl)
for easier debugging.
<br>
<br>
For more information on precompiling templates see
[lodash's custom builds documentation](https://lodash.com/custom-builds).
<br>
<br>
For more information on Chrome extension sandboxes see
[Chrome's extensions documentation](https://developer.chrome.com/extensions/sandboxingEval).

#### 起始版本
0.1.0
#### 参数
1. `[string='']` *(string)*: The template string.
2. `[options={}]` *(Object)*: The options object.
3. `[options.escape=_.templateSettings.escape]` *(RegExp)*: The HTML "escape" delimiter.
4. `[options.evaluate=_.templateSettings.evaluate]` *(RegExp)*: The "evaluate" delimiter.
5. `[options.imports=_.templateSettings.imports]` *(Object)*: An object to import into the template as free variables.
6. `[options.interpolate=_.templateSettings.interpolate]` *(RegExp)*: The "interpolate" delimiter.
7. `[options.sourceURL='lodash.templateSources[n]']` *(string)*: The sourceURL of the compiled template.
8. `[options.variable='obj']` *(string)*: The data object variable name.

#### 返回结果
*(Function)*: Returns the compiled template function.

####示例
```js
// Use the "interpolate" delimiter to create a compiled template.
var compiled = _.template('hello <%= user %>!');
compiled({ 'user': 'fred' });
// => 'hello fred!'

// Use the HTML "escape" delimiter to escape data property values.
var compiled = _.template('<b><%- value %></b>');
compiled({ 'value': '<script>' });
// => '<b>&lt;script&gt;</b>'

// Use the "evaluate" delimiter to execute JavaScript and generate HTML.
var compiled = _.template('<% _.forEach(users, function(user) { %><li><%- user %></li><% }); %>');
compiled({ 'users': ['fred', 'barney'] });
// => '<li>fred</li><li>barney</li>'

// Use the internal `print` function in "evaluate" delimiters.
var compiled = _.template('<% print("hello " + user); %>!');
compiled({ 'user': 'barney' });
// => 'hello barney!'

// Use the ES template literal delimiter as an "interpolate" delimiter.
// Disable support by replacing the "interpolate" delimiter.
var compiled = _.template('hello ${ user }!');
compiled({ 'user': 'pebbles' });
// => 'hello pebbles!'

// Use backslashes to treat delimiters as plain text.
var compiled = _.template('<%= "\\<%- value %\\>" %>');
compiled({ 'value': 'ignored' });
// => '<%- value %>'

// Use the `imports` option to import `jQuery` as `jq`.
var text = '<% jq.each(users, function(user) { %><li><%- user %></li><% }); %>';
var compiled = _.template(text, { 'imports': { 'jq': jQuery } });
compiled({ 'users': ['fred', 'barney'] });
// => '<li>fred</li><li>barney</li>'

// Use the `sourceURL` option to specify a custom sourceURL for the template.
var compiled = _.template('hello <%= user %>!', { 'sourceURL': '/basic/greeting.jst' });
compiled(data);
// => Find the source of "greeting.jst" under the Sources tab or Resources panel of the web inspector.

// Use the `variable` option to ensure a with-statement isn't used in the compiled template.
var compiled = _.template('hi <%= data.user %>!', { 'variable': 'data' });
compiled.source;
// => function(data) {
//   var __t, __p = '';
//   __p += 'hi ' + ((__t = ( data.user )) == null ? '' : __t) + '!';
//   return __p;
// }

// Use custom template delimiters.
_.templateSettings.interpolate = /{{([\s\S]+?)}}/g;
var compiled = _.template('hello {{ user }}!');
compiled({ 'user': 'mustache' });
// => 'hello mustache!'

// Use the `source` property to inline compiled templates for meaningful
// line numbers in error messages and stack traces.
fs.writeFileSync(path.join(process.cwd(), 'jst.js'), '\
  var JST = {\
    "main": ' + _.template(mainText).source + '\
  };\
');
```
---

<!-- /div -->

<!-- div -->

<h3 id="_tolowerstring"><code>_.toLower([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14687 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.tolower "查看Npm包") [&#x24C9;][1]

Converts `string`, as a whole, to lower case just like
[String#toLowerCase](https://mdn.io/toLowerCase).

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the lower cased string.

####示例
```js
_.toLower('--Foo-Bar--');
// => '--foo-bar--'

_.toLower('fooBar');
// => 'foobar'

_.toLower('__FOO_BAR__');
// => '__foo_bar__'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_toupperstring"><code>_.toUpper([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14712 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.toupper "查看Npm包") [&#x24C9;][1]

Converts `string`, as a whole, to upper case just like
[String#toUpperCase](https://mdn.io/toUpperCase).

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the upper cased string.

####示例
```js
_.toUpper('--foo-bar--');
// => '--FOO-BAR--'

_.toUpper('fooBar');
// => 'FOOBAR'

_.toUpper('__foo_bar__');
// => '__FOO_BAR__'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_trimstring-charswhitespace"><code>_.trim([string=''], [chars=whitespace])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14738 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.trim "查看Npm包") [&#x24C9;][1]

Removes leading and trailing whitespace or specified characters from `string`.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to trim.
2. `[chars=whitespace]` *(string)*: The characters to trim.

#### 返回结果
*(string)*: Returns the trimmed string.

####示例
```js
_.trim('  abc  ');
// => 'abc'

_.trim('-_-abc-_-', '_-');
// => 'abc'

_.map(['  foo  ', '  bar  '], _.trim);
// => ['foo', 'bar']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_trimendstring-charswhitespace"><code>_.trimEnd([string=''], [chars=whitespace])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14773 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.trimend "查看Npm包") [&#x24C9;][1]

Removes trailing whitespace or specified characters from `string`.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to trim.
2. `[chars=whitespace]` *(string)*: The characters to trim.

#### 返回结果
*(string)*: Returns the trimmed string.

####示例
```js
_.trimEnd('  abc  ');
// => '  abc'

_.trimEnd('-_-abc-_-', '_-');
// => '-_-abc'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_trimstartstring-charswhitespace"><code>_.trimStart([string=''], [chars=whitespace])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14806 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.trimstart "查看Npm包") [&#x24C9;][1]

Removes leading whitespace or specified characters from `string`.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to trim.
2. `[chars=whitespace]` *(string)*: The characters to trim.

#### 返回结果
*(string)*: Returns the trimmed string.

####示例
```js
_.trimStart('  abc  ');
// => 'abc  '

_.trimStart('-_-abc-_-', '_-');
// => 'abc-_-'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_truncatestring-options"><code>_.truncate([string=''], [options={}])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14857 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.truncate "查看Npm包") [&#x24C9;][1]

Truncates `string` if it's longer than the given maximum string length.
The last characters of the truncated string are replaced with the omission
string which defaults to "...".

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to truncate.
2. `[options={}]` *(Object)*: The options object.
3. `[options.length=30]` *(number)*: The maximum string length.
4. `[options.omission='...']` *(string)*: The string to indicate text is omitted.
5. `[options.separator]` *(RegExp|string)*: The separator pattern to truncate to.

#### 返回结果
*(string)*: Returns the truncated string.

####示例
```js
_.truncate('hi-diddly-ho there, neighborino');
// => 'hi-diddly-ho there, neighbo...'

_.truncate('hi-diddly-ho there, neighborino', {
  'length': 24,
  'separator': ' '
});
// => 'hi-diddly-ho there,...'

_.truncate('hi-diddly-ho there, neighborino', {
  'length': 24,
  'separator': /,? +/
});
// => 'hi-diddly-ho there...'

_.truncate('hi-diddly-ho there, neighborino', {
  'omission': ' [...]'
});
// => 'hi-diddly-ho there, neig [...]'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_unescapestring"><code>_.unescape([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14932 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.unescape "查看Npm包") [&#x24C9;][1]

The inverse of `_.escape`; this method converts the HTML entities
`&amp;`, `&lt;`, `&gt;`, `&quot;`, and `&#39;` in `string` to
their corresponding characters.
<br>
<br>
**提示:** No other HTML entities are unescaped. To unescape additional
HTML entities use a third-party library like [_he_](https://mths.be/he).

#### 起始版本
0.6.0
#### 参数
1. `[string='']` *(string)*: The string to unescape.

#### 返回结果
*(string)*: Returns the unescaped string.

####示例
```js
_.unescape('fred, barney, &amp; pebbles');
// => 'fred, barney, & pebbles'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_uppercasestring"><code>_.upperCase([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14959 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.uppercase "查看Npm包") [&#x24C9;][1]

Converts `string`, as space separated words, to upper case.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the upper cased string.

####示例
```js
_.upperCase('--foo-bar');
// => 'FOO BAR'

_.upperCase('fooBar');
// => 'FOO BAR'

_.upperCase('__foo_bar__');
// => 'FOO BAR'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_upperfirststring"><code>_.upperFirst([string=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L14980 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.upperfirst "查看Npm包") [&#x24C9;][1]

Converts the first character of `string` to upper case.

#### 起始版本
4.0.0
#### 参数
1. `[string='']` *(string)*: The string to convert.

#### 返回结果
*(string)*: Returns the converted string.

####示例
```js
_.upperFirst('fred');
// => 'Fred'

_.upperFirst('FRED');
// => 'FRED'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_wordsstring-pattern"><code>_.words([string=''], [pattern])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15001 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.words "查看Npm包") [&#x24C9;][1]

Splits `string` into an array of its words.

#### 起始版本
3.0.0
#### 参数
1. `[string='']` *(string)*: The string to inspect.
2. `[pattern]` *(RegExp|string)*: The pattern to match words.

#### 返回结果
*(Array)*: Returns the words of `string`.

####示例
```js
_.words('fred, barney, & pebbles');
// => ['fred', 'barney', 'pebbles']

_.words('fred, barney, & pebbles', /[^, ]+/g);
// => ['fred', 'barney', '&', 'pebbles']
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `“Util” Methods`

<!-- div -->

<h3 id="_attemptfunc-args"><code>_.attempt(func, [args])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15035 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.attempt "查看Npm包") [&#x24C9;][1]

Attempts to invoke `func`, returning either the result or the caught error
object. Any additional arguments are provided to `func` when it's invoked.

#### 起始版本
3.0.0
#### 参数
1. `func` *(Function)*: The function to attempt.
2. `[args]` *(...&#42;)*: The arguments to invoke `func` with.

#### 返回结果
*(&#42;)*: Returns the `func` result or error object.

####示例
```js
// Avoid throwing errors for invalid selectors.
var elements = _.attempt(function(selector) {
  return document.querySelectorAll(selector);
}, '>_>');

if (_.isError(elements)) {
  elements = [];
}
```
---

<!-- /div -->

<!-- div -->

<h3 id="_bindallobject-methodnames"><code>_.bindAll(object, methodNames)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15069 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.bindall "查看Npm包") [&#x24C9;][1]

Binds methods of an object to the object itself, overwriting the existing
method.
<br>
<br>
**提示:** This method doesn't set the "length" property of bound functions.

#### 起始版本
0.1.0
#### 参数
1. `object` *(Object)*: The object to bind and assign the bound methods to.
2. `methodNames` *(...(string|string&#91;&#93;))*: The object method names to bind.

#### 返回结果
*(Object)*: Returns `object`.

####示例
```js
var view = {
  'label': 'docs',
  'click': function() {
    console.log('clicked ' + this.label);
  }
};

_.bindAll(view, ['click']);
jQuery(element).on('click', view.click);
// => Logs 'clicked docs' when clicked.
```
---

<!-- /div -->

<!-- div -->

<h3 id="_condpairs"><code>_.cond(pairs)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15106 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.cond "查看Npm包") [&#x24C9;][1]

Creates a function that iterates over `pairs` and invokes the corresponding
function of the first predicate to return truthy. The predicate-function
pairs are invoked with the `this` binding and arguments of the created
function.

#### 起始版本
4.0.0
#### 参数
1. `pairs` *(Array)*: The predicate-function pairs.

#### 返回结果
*(Function)*: Returns the new composite function.

####示例
```js
var func = _.cond([
  [_.matches({ 'a': 1 }),           _.constant('matches A')],
  [_.conforms({ 'b': _.isNumber }), _.constant('matches B')],
  [_.stubTrue,                      _.constant('no match')]
]);

func({ 'a': 1, 'b': 2 });
// => 'matches A'

func({ 'a': 0, 'b': 1 });
// => 'matches B'

func({ 'a': '1', 'b': '2' });
// => 'no match'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_conformssource"><code>_.conforms(source)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15152 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.conforms "查看Npm包") [&#x24C9;][1]

Creates a function that invokes the predicate properties of `source` with
the corresponding property values of a given object, returning `true` if
all predicates return truthy, else `false`.
<br>
<br>
**提示:** The created function is equivalent to `_.conformsTo` with
`source` partially applied.

#### 起始版本
4.0.0
#### 参数
1. `source` *(Object)*: The object of property predicates to conform to.

#### 返回结果
*(Function)*: Returns the new spec function.

####示例
```js
var objects = [
  { 'a': 2, 'b': 1 },
  { 'a': 1, 'b': 2 }
];

_.filter(objects, _.conforms({ 'b': function(n) { return n > 1; } }));
// => [{ 'a': 1, 'b': 2 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_constantvalue"><code>_.constant(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15175 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.constant "查看Npm包") [&#x24C9;][1]

Creates a function that returns `value`.

#### 起始版本
2.4.0
#### 参数
1. `value` *(&#42;)*: The value to return from the new function.

#### 返回结果
*(Function)*: Returns the new constant function.

####示例
```js
var objects = _.times(2, _.constant({ 'a': 1 }));

console.log(objects);
// => [{ 'a': 1 }, { 'a': 1 }]

console.log(objects[0] === objects[1]);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_defaulttovalue-defaultvalue"><code>_.defaultTo(value, defaultValue)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15201 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.defaultto "查看Npm包") [&#x24C9;][1]

Checks `value` to determine whether a default value should be returned in
its place. The `defaultValue` is returned if `value` is `NaN`, `null`,
or `undefined`.

#### 起始版本
4.14.0
#### 参数
1. `value` *(&#42;)*: The value to check.
2. `defaultValue` *(&#42;)*: The default value.

#### 返回结果
*(&#42;)*: Returns the resolved value.

####示例
```js
_.defaultTo(1, 10);
// => 1

_.defaultTo(undefined, 10);
// => 10
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flowfuncs"><code>_.flow([funcs])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15227 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flow "查看Npm包") [&#x24C9;][1]

Creates a function that returns the result of invoking the given functions
with the `this` binding of the created function, where each successive
invocation is supplied the return value of the previous.

#### 起始版本
3.0.0
#### 参数
1. `[funcs]` *(...(Function|Function&#91;&#93;))*: The functions to invoke.

#### 返回结果
*(Function)*: Returns the new composite function.

####示例
```js
function square(n) {
  return n * n;
}

var addSquare = _.flow([_.add, square]);
addSquare(1, 2);
// => 9
```
---

<!-- /div -->

<!-- div -->

<h3 id="_flowrightfuncs"><code>_.flowRight([funcs])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15250 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.flowright "查看Npm包") [&#x24C9;][1]

This method is like `_.flow` except that it creates a function that
invokes the given functions from right to left.

#### 起始版本
3.0.0
#### 参数
1. `[funcs]` *(...(Function|Function&#91;&#93;))*: The functions to invoke.

#### 返回结果
*(Function)*: Returns the new composite function.

####示例
```js
function square(n) {
  return n * n;
}

var addSquare = _.flowRight([square, _.add]);
addSquare(1, 2);
// => 9
```
---

<!-- /div -->

<!-- div -->

<h3 id="_identityvalue"><code>_.identity(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15268 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.identity "查看Npm包") [&#x24C9;][1]

This method returns the first argument it receives.

#### 起始版本
0.1.0
#### 参数
1. `value` *(&#42;)*: Any value.

#### 返回结果
*(&#42;)*: Returns `value`.

####示例
```js
var object = { 'a': 1 };

console.log(_.identity(object) === object);
// => true
```
---

<!-- /div -->

<!-- div -->

<h3 id="_iterateefunc_identity"><code>_.iteratee([func=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15314 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.iteratee "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `func` with the arguments of the created
function. If `func` is a property name, the created function returns the
property value for a given element. If `func` is an array or object, the
created function returns `true` for elements that contain the equivalent
source properties, otherwise it returns `false`.

#### 起始版本
4.0.0
#### 参数
1. `[func=_.identity]` *(&#42;)*: The value to convert to a callback.

#### 返回结果
*(Function)*: Returns the callback.

####示例
```js
var users = [
  { 'user': 'barney', 'age': 36, 'active': true },
  { 'user': 'fred',   'age': 40, 'active': false }
];

// The `_.matches` 的缩写
_.filter(users, _.iteratee({ 'user': 'barney', 'active': true }));
// => [{ 'user': 'barney', 'age': 36, 'active': true }]

// The `_.matchesProperty` 的缩写
_.filter(users, _.iteratee(['user', 'fred']));
// => [{ 'user': 'fred', 'age': 40 }]

// The `_.property` 的缩写
_.map(users, _.iteratee('user'));
// => ['barney', 'fred']

// Create custom iteratee shorthands.
_.iteratee = _.wrap(_.iteratee, function(iteratee, func) {
  return !_.isRegExp(func) ? iteratee(func) : function(string) {
    return func.test(string);
  };
});

_.filter(['abc', 'def'], /ef/);
// => ['def']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_matchessource"><code>_.matches(source)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15346 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.matches "查看Npm包") [&#x24C9;][1]

Creates a function that performs a partial deep comparison between a given
object and `source`, returning `true` if the given object has equivalent
property values, else `false`.
<br>
<br>
**提示:** The created function is equivalent to `_.isMatch` with `source`
partially applied.
<br>
<br>
Partial comparisons will match empty array and empty object `source`
values against any array or object value, respectively. See `_.isEqual`
for a list of supported value comparisons.

#### 起始版本
3.0.0
#### 参数
1. `source` *(Object)*: The object of property values to match.

#### 返回结果
*(Function)*: Returns the new spec function.

####示例
```js
var objects = [
  { 'a': 1, 'b': 2, 'c': 3 },
  { 'a': 4, 'b': 5, 'c': 6 }
];

_.filter(objects, _.matches({ 'a': 4, 'c': 6 }));
// => [{ 'a': 4, 'b': 5, 'c': 6 }]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_matchespropertypath-srcvalue"><code>_.matchesProperty(path, srcValue)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15376 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.matchesproperty "查看Npm包") [&#x24C9;][1]

Creates a function that performs a partial deep comparison between the
value at `path` of a given object to `srcValue`, returning `true` if the
object value is equivalent, else `false`.
<br>
<br>
**提示:** Partial comparisons will match empty array and empty object
`srcValue` values against any array or object value, respectively. See
`_.isEqual` for a list of supported value comparisons.

#### 起始版本
3.2.0
#### 参数
1. `path` *(Array|string)*: The path of the property to get.
2. `srcValue` *(&#42;)*: The value to match.

#### 返回结果
*(Function)*: Returns the new spec function.

####示例
```js
var objects = [
  { 'a': 1, 'b': 2, 'c': 3 },
  { 'a': 4, 'b': 5, 'c': 6 }
];

_.find(objects, _.matchesProperty('a', 4));
// => { 'a': 4, 'b': 5, 'c': 6 }
```
---

<!-- /div -->

<!-- div -->

<h3 id="_methodpath-args"><code>_.method(path, [args])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15404 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.method "查看Npm包") [&#x24C9;][1]

Creates a function that invokes the method at `path` of a given object.
Any additional arguments are provided to the invoked method.

#### 起始版本
3.7.0
#### 参数
1. `path` *(Array|string)*: The path of the method to invoke.
2. `[args]` *(...&#42;)*: The arguments to invoke the method with.

#### 返回结果
*(Function)*: Returns the new invoker function.

####示例
```js
var objects = [
  { 'a': { 'b': _.constant(2) } },
  { 'a': { 'b': _.constant(1) } }
];

_.map(objects, _.method('a.b'));
// => [2, 1]

_.map(objects, _.method(['a', 'b']));
// => [2, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_methodofobject-args"><code>_.methodOf(object, [args])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15433 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.methodof "查看Npm包") [&#x24C9;][1]

The opposite of `_.method`; this method creates a function that invokes
the method at a given path of `object`. Any additional arguments are
provided to the invoked method.

#### 起始版本
3.7.0
#### 参数
1. `object` *(Object)*: The object to query.
2. `[args]` *(...&#42;)*: The arguments to invoke the method with.

#### 返回结果
*(Function)*: Returns the new invoker function.

####示例
```js
var array = _.times(3, _.constant),
    object = { 'a': array, 'b': array, 'c': array };

_.map(['a[2]', 'c[0]'], _.methodOf(object));
// => [2, 0]

_.map([['a', '2'], ['c', '0']], _.methodOf(object));
// => [2, 0]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_mixinobjectlodash-source-options"><code>_.mixin([object=lodash], source, [options={}])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15475 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.mixin "查看Npm包") [&#x24C9;][1]

Adds all own enumerable string keyed function properties of a source
object to the destination object. If `object` is a function, then methods
are added to its prototype as well.
<br>
<br>
**提示:** Use `_.runInContext` to create a pristine `lodash` function to
avoid conflicts caused by modifying the original.

#### 起始版本
0.1.0
#### 参数
1. `[object=lodash]` *(Function|Object)*: The destination object.
2. `source` *(Object)*: The object of functions to add.
3. `[options={}]` *(Object)*: The options object.
4. `[options.chain=true]` *(boolean)*: Specify whether mixins are chainable.

#### 返回结果
*(&#42;)*: Returns `object`.

####示例
```js
function vowels(string) {
  return _.filter(string, function(v) {
    return /[aeiou]/i.test(v);
  });
}

_.mixin({ 'vowels': vowels });
_.vowels('fred');
// => ['e']

_('fred').vowels().value();
// => ['e']

_.mixin({ 'vowels': vowels }, { 'chain': false });
_('fred').vowels();
// => ['e']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_noconflict"><code>_.noConflict()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15524 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.noconflict "查看Npm包") [&#x24C9;][1]

Reverts the `_` variable to its previous value and returns a reference to
the `lodash` function.

#### 起始版本
0.1.0
#### 返回结果
*(Function)*: Returns the `lodash` function.

####示例
```js
var lodash = _.noConflict();
```
---

<!-- /div -->

<!-- div -->

<h3 id="_noop"><code>_.noop()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15543 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.noop "查看Npm包") [&#x24C9;][1]

This method returns `undefined`.

#### 起始版本
2.3.0
####示例
```js
_.times(2, _.noop);
// => [undefined, undefined]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_nthargn0"><code>_.nthArg([n=0])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15567 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.ntharg "查看Npm包") [&#x24C9;][1]

Creates a function that gets the argument at index `n`. If `n` is negative,
the nth argument from the end is returned.

#### 起始版本
4.0.0
#### 参数
1. `[n=0]` *(number)*: The index of the argument to return.

#### 返回结果
*(Function)*: Returns the new pass-thru function.

####示例
```js
var func = _.nthArg(1);
func('a', 'b', 'c', 'd');
// => 'b'

var func = _.nthArg(-2);
func('a', 'b', 'c', 'd');
// => 'c'
```
---

<!-- /div -->

<!-- div -->

<h3 id="_overiteratees_identity"><code>_.over([iteratees=[_.identity]])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15592 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.over "查看Npm包") [&#x24C9;][1]

Creates a function that invokes `iteratees` with the arguments it receives
and returns their results.

#### 起始版本
4.0.0
#### 参数
1. `[iteratees=[_.identity]]` *(...(Function|Function&#91;&#93;))*: The iteratees to invoke.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
var func = _.over([Math.max, Math.min]);

func(1, 2, 3, 4);
// => [4, 1]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_overeverypredicates_identity"><code>_.overEvery([predicates=[_.identity]])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15618 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.overevery "查看Npm包") [&#x24C9;][1]

Creates a function that checks if **all** of the `predicates` return
truthy when invoked with the arguments it receives.

#### 起始版本
4.0.0
#### 参数
1. `[predicates=[_.identity]]` *(...(Function|Function&#91;&#93;))*: The predicates to check.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
var func = _.overEvery([Boolean, isFinite]);

func('1');
// => true

func(null);
// => false

func(NaN);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_oversomepredicates_identity"><code>_.overSome([predicates=[_.identity]])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15644 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.oversome "查看Npm包") [&#x24C9;][1]

Creates a function that checks if **any** of the `predicates` return
truthy when invoked with the arguments it receives.

#### 起始版本
4.0.0
#### 参数
1. `[predicates=[_.identity]]` *(...(Function|Function&#91;&#93;))*: The predicates to check.

#### 返回结果
*(Function)*: Returns the new function.

####示例
```js
var func = _.overSome([Boolean, isFinite]);

func('1');
// => true

func(null);
// => true

func(NaN);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_propertypath"><code>_.property(path)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15668 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.property "查看Npm包") [&#x24C9;][1]

Creates a function that returns the value at `path` of a given object.

#### 起始版本
2.4.0
#### 参数
1. `path` *(Array|string)*: The path of the property to get.

#### 返回结果
*(Function)*: Returns the new accessor function.

####示例
```js
var objects = [
  { 'a': { 'b': 2 } },
  { 'a': { 'b': 1 } }
];

_.map(objects, _.property('a.b'));
// => [2, 1]

_.map(_.sortBy(objects, _.property(['a', 'b'])), 'a.b');
// => [1, 2]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_propertyofobject"><code>_.propertyOf(object)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15693 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.propertyof "查看Npm包") [&#x24C9;][1]

The opposite of `_.property`; this method creates a function that returns
the value at a given path of `object`.

#### 起始版本
3.0.0
#### 参数
1. `object` *(Object)*: The object to query.

#### 返回结果
*(Function)*: Returns the new accessor function.

####示例
```js
var array = [0, 1, 2],
    object = { 'a': array, 'b': array, 'c': array };

_.map(['a[2]', 'c[0]'], _.propertyOf(object));
// => [2, 0]

_.map([['a', '2'], ['c', '0']], _.propertyOf(object));
// => [2, 0]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_rangestart0-end-step1"><code>_.range([start=0], end, [step=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15740 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.range "查看Npm包") [&#x24C9;][1]

Creates an array of numbers *(positive and/or negative)* progressing from
`start` up to, but not including, `end`. A step of `-1` is used if a negative
`start` is specified without an `end` or `step`. If `end` is not specified,
it's set to `start` with `start` then set to `0`.
<br>
<br>
**提示:** JavaScript follows the IEEE-754 standard for resolving
floating-point values which can produce unexpected results.

#### 起始版本
0.1.0
#### 参数
1. `[start=0]` *(number)*: The start of the range.
2. `end` *(number)*: The end of the range.
3. `[step=1]` *(number)*: The value to increment or decrement by.

#### 返回结果
*(Array)*: Returns the range of numbers.

####示例
```js
_.range(4);
// => [0, 1, 2, 3]

_.range(-4);
// => [0, -1, -2, -3]

_.range(1, 5);
// => [1, 2, 3, 4]

_.range(0, 20, 5);
// => [0, 5, 10, 15]

_.range(0, -4, -1);
// => [0, -1, -2, -3]

_.range(1, 4, 0);
// => [1, 1, 1]

_.range(0);
// => []
```
---

<!-- /div -->

<!-- div -->

<h3 id="_rangerightstart0-end-step1"><code>_.rangeRight([start=0], end, [step=1])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15778 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.rangeright "查看Npm包") [&#x24C9;][1]

This method is like `_.range` except that it populates values in
descending order.

#### 起始版本
4.0.0
#### 参数
1. `[start=0]` *(number)*: The start of the range.
2. `end` *(number)*: The end of the range.
3. `[step=1]` *(number)*: The value to increment or decrement by.

#### 返回结果
*(Array)*: Returns the range of numbers.

####示例
```js
_.rangeRight(4);
// => [3, 2, 1, 0]

_.rangeRight(-4);
// => [-3, -2, -1, 0]

_.rangeRight(1, 5);
// => [4, 3, 2, 1]

_.rangeRight(0, 20, 5);
// => [15, 10, 5, 0]

_.rangeRight(0, -4, -1);
// => [-3, -2, -1, 0]

_.rangeRight(1, 4, 0);
// => [1, 1, 1]

_.rangeRight(0);
// => []
```
---

<!-- /div -->

<!-- div -->

<h3 id="_runincontextcontextroot"><code>_.runInContext([context=root])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1410 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.runincontext "查看Npm包") [&#x24C9;][1]

Create a new pristine `lodash` function using the `context` object.

#### 起始版本
1.1.0
#### 参数
1. `[context=root]` *(Object)*: The context object.

#### 返回结果
*(Function)*: Returns a new `lodash` function.

####示例
```js
_.mixin({ 'foo': _.constant('foo') });

var lodash = _.runInContext();
lodash.mixin({ 'bar': lodash.constant('bar') });

_.isFunction(_.foo);
// => true
_.isFunction(_.bar);
// => false

lodash.isFunction(lodash.foo);
// => false
lodash.isFunction(lodash.bar);
// => true

// Create a suped-up `defer` in Node.js.
var defer = _.runInContext({ 'setTimeout': setImmediate }).defer;
```
---

<!-- /div -->

<!-- div -->

<h3 id="_stubarray"><code>_.stubArray()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15798 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.stubarray "查看Npm包") [&#x24C9;][1]

This method returns a new empty array.

#### 起始版本
4.13.0
#### 返回结果
*(Array)*: Returns the new empty array.

####示例
```js
var arrays = _.times(2, _.stubArray);

console.log(arrays);
// => [[], []]

console.log(arrays[0] === arrays[1]);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_stubfalse"><code>_.stubFalse()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15815 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.stubfalse "查看Npm包") [&#x24C9;][1]

This method returns `false`.

#### 起始版本
4.13.0
#### 返回结果
*(boolean)*: Returns `false`.

####示例
```js
_.times(2, _.stubFalse);
// => [false, false]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_stubobject"><code>_.stubObject()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15837 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.stubobject "查看Npm包") [&#x24C9;][1]

This method returns a new empty object.

#### 起始版本
4.13.0
#### 返回结果
*(Object)*: Returns the new empty object.

####示例
```js
var objects = _.times(2, _.stubObject);

console.log(objects);
// => [{}, {}]

console.log(objects[0] === objects[1]);
// => false
```
---

<!-- /div -->

<!-- div -->

<h3 id="_stubstring"><code>_.stubString()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15854 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.stubstring "查看Npm包") [&#x24C9;][1]

This method returns an empty string.

#### 起始版本
4.13.0
#### 返回结果
*(string)*: Returns the empty string.

####示例
```js
_.times(2, _.stubString);
// => ['', '']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_stubtrue"><code>_.stubTrue()</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15871 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.stubtrue "查看Npm包") [&#x24C9;][1]

This method returns `true`.

#### 起始版本
4.13.0
#### 返回结果
*(boolean)*: Returns `true`.

####示例
```js
_.times(2, _.stubTrue);
// => [true, true]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_timesn-iteratee_identity"><code>_.times(n, [iteratee=_.identity])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15894 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.times "查看Npm包") [&#x24C9;][1]

Invokes the iteratee `n` times, returning an array of the results of
each invocation. The iteratee is invoked with one argument; *(index)*.

#### 起始版本
0.1.0
#### 参数
1. `n` *(number)*: The number of times to invoke `iteratee`.
2. `[iteratee=_.identity]` *(Function)*: The function invoked per iteration.

#### 返回结果
*(Array)*: Returns the array of results.

####示例
```js
_.times(3, String);
// => ['0', '1', '2']

 _.times(4, _.constant(0));
// => [0, 0, 0, 0]
```
---

<!-- /div -->

<!-- div -->

<h3 id="_topathvalue"><code>_.toPath(value)</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15929 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.topath "查看Npm包") [&#x24C9;][1]

Converts `value` to a property path array.

#### 起始版本
4.0.0
#### 参数
1. `value` *(&#42;)*: The value to convert.

#### 返回结果
*(Array)*: Returns the new property path array.

####示例
```js
_.toPath('a.b.c');
// => ['a', 'b', 'c']

_.toPath('a[0].b.c');
// => ['a', '0', 'b', 'c']
```
---

<!-- /div -->

<!-- div -->

<h3 id="_uniqueidprefix"><code>_.uniqueId([prefix=''])</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L15953 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.uniqueid "查看Npm包") [&#x24C9;][1]

Generates a unique ID. If `prefix` is given, the ID is appended to it.

#### 起始版本
0.1.0
#### 参数
1. `[prefix='']` *(string)*: The value to prefix the ID with.

#### 返回结果
*(string)*: Returns the unique ID.

####示例
```js
_.uniqueId('contact_');
// => 'contact_104'

_.uniqueId();
// => '105'
```
---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `Properties`

<!-- div -->

<h3 id="_version"><code>_.VERSION</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L16644 "查看源码") [&#x24C9;][1]

(string): The semantic version number.

---

<!-- /div -->

<!-- div -->

<h3 id="_templatesettings"><code>_.templateSettings</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1689 "查看源码") [&#x24C3;](https://www.npmjs.com/package/lodash.templatesettings "查看Npm包") [&#x24C9;][1]

(Object): By default, the template delimiters used by lodash are like those in
embedded Ruby *(ERB)*. Change the following template settings to use
alternative delimiters.

---

<!-- /div -->

<!-- div -->

<h3 id="_templatesettingsescape"><code>_.templateSettings.escape</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1697 "查看源码") [&#x24C9;][1]

(RegExp): Used to detect `data` property values to be HTML-escaped.

---

<!-- /div -->

<!-- div -->

<h3 id="_templatesettingsevaluate"><code>_.templateSettings.evaluate</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1705 "查看源码") [&#x24C9;][1]

(RegExp): Used to detect code to be evaluated.

---

<!-- /div -->

<!-- div -->

<h3 id="_templatesettingsimports"><code>_.templateSettings.imports</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1729 "查看源码") [&#x24C9;][1]

(Object): Used to import variables into the compiled template.

---

<!-- /div -->

<!-- div -->

<h3 id="_templatesettingsinterpolate"><code>_.templateSettings.interpolate</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1713 "查看源码") [&#x24C9;][1]

(RegExp): Used to detect `data` property values to inject.

---

<!-- /div -->

<!-- div -->

<h3 id="_templatesettingsvariable"><code>_.templateSettings.variable</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1721 "查看源码") [&#x24C9;][1]

(string): Used to reference the data object in the template text.

---

<!-- /div -->

<!-- /div -->

<!-- div -->

## `Methods`

<!-- div -->

<h3 id="_templatesettingsimports_"><code>_.templateSettings.imports._</code></h3>
[&#x24C8;](https://github.com/lodash/lodash/blob/4.16.1/lodash.js#L1737 "查看源码") [&#x24C9;][1]

A reference to the `lodash` function.

---

<!-- /div -->

<!-- /div -->

<!-- /div -->

 [1]: #array "返回Top"
